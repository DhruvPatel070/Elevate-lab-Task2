# Elevate-lab-Task2

# Task 2 – Operating System Security Fundamentals (Linux & Windows)

## Student Details
- **Name:** Patel Dhruv Nirmalkumar  
- **Email:** dhruvpatel.00700@gmail.com  
- **Phone:** 9426176903  
- **Task Number:** 2  

---

## Exploring User Accounts, Permissions, and Access Control

- Linux supports multiple user accounts, each with specific access rights.
- User account information is stored in `/etc/passwd`.
- Password-related data is stored securely in `/etc/shadow`.
- Access control ensures users can access only the files and system resources they are authorized to use.
- This helps reduce unauthorized access and privilege misuse.

---

## Understanding File Permissions Using `chmod`, `chown`, and `ls -l`

### Definition
File permissions control who can read, write, or execute a file or directory in Linux.

### Explanation
Linux uses three types of permissions:

- **Read (r):** View file content  
- **Write (w):** Modify file content  
- **Execute (x):** Run the file as a program  

Permissions are applied to three user categories:

- Owner  
- Group  
- Others  

chmod 755 file.sh

## File Permission Example Explanation

- **Owner** can read, write, and execute  
- **Group** can read and execute  
- **Others** can read and execute  

---

## Administrator vs Standard User Privileges

- The **root (administrator)** user has complete control over the system.
- A **standard user** has limited permissions and cannot make critical system changes.
- Using standard accounts for daily work reduces the impact of malware and accidental damage.
- Administrative access should be used only when required.

### Key Point
- Root is powerful but dangerous.
- Normal users protect the system by default.

---

## Enabling Firewall (UFW or Windows Firewall)

- A firewall monitors and controls incoming and outgoing network traffic.
- In Linux, **UFW (Uncomplicated Firewall)** is enabled to block unauthorized connections.
- In Windows, **Windows Defender Firewall** provides similar protection.
- Firewalls are a basic but essential layer of OS security.

---

## Identifying Running Processes and Services

- Running processes show which programs are currently active on the system.
- Commands like `ps`, `top`, and `htop` help monitor system activity in Linux.
- On Windows, **Task Manager** displays running processes and services.
- Monitoring processes helps detect suspicious or unwanted activity.

---

## Disabling Unnecessary Services to Reduce Attack Surface

- Unused services increase the system’s attack surface.
- Attackers often exploit unnecessary background services.
- Disabling unused services improves both performance and security.
- Only essential services should be allowed to run.

---

## Best OS Hardening Practices

- Keep the operating system updated with the latest patches.
- Use strong passwords and enable account lockout policies.
- Apply the principle of least privilege.
- Enable firewalls and antivirus protection.
- Disable unnecessary services and open ports.
- Regularly audit users, permissions, and system logs.

---

## Final Outcome

- This task builds a strong understanding of OS-level security and hardening.
- It demonstrates how proper system configuration reduces security risks at the operating system level.

---

## Deliverable – OS Security Checklist

### Linux / Windows OS Hardening Checklist

- Installed OS from a trusted source
- Created standard user accounts (not using admin daily)
- Used strong passwords
- Applied latest security updates
- Verified user accounts and removed unused ones
- Configured file permissions properly
- Used `chmod`, `chown`, and `ls -l` (Linux)
- Enabled firewall:
  - UFW on Linux
  - Windows Defender Firewall on Windows
- Checked running processes and services
- Disabled unnecessary services
- Limited root or administrator access
- Followed the principle of least privilege
