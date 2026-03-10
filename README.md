Windows 11 Endpoint Security Hardening Project
Overview

This project documents the process of hardening a Windows 11 Pro system to improve its security posture and reduce the risk of compromise. The objective was to simulate real-world enterprise endpoint security practices by implementing layered defensive controls and applying system hardening techniques.

The project focuses on reducing attack surface, enforcing least privilege, protecting data through encryption, and strengthening built-in security tools.

This project demonstrates practical experience in:

Endpoint security

Operating system hardening

Security configuration

System monitoring

Defensive cybersecurity practices

Objectives

The primary goals of this project were to:

Reduce the system’s attack surface

Implement least privilege access control

Protect sensitive data using full disk encryption

Strengthen built-in Windows security tools

Improve system visibility and monitoring

Simulate enterprise security hardening practices

System Environment

Operating System:
Windows 11 Pro

Hardware Security:
TPM-enabled device

Security Tools Used:

Microsoft Defender Antivirus

Windows Defender Firewall

BitLocker

Windows Security Center

Windows Event Viewer

Microsoft SmartScreen

Security Hardening Implementation
Account Security & Access Control

To reduce the risk of privilege escalation and unauthorized access, the system was configured using the principle of least privilege.

Implemented controls:

Created separate administrator and standard user accounts

Daily computing performed under a standard user account

Administrator account used only for system changes

Configured User Account Control (UAC) to a strict level

Removed or disabled unnecessary accounts

This reduces the likelihood that malware can gain administrative privileges.

Disk Encryption & Data Protection

Full disk encryption was enabled using BitLocker to protect data in case of device theft or physical compromise.

Configuration included:

Enabled BitLocker full disk encryption

Utilized TPM-backed encryption

Stored BitLocker recovery key securely

Verified recovery access procedure

This ensures that stored data cannot be accessed without proper authentication.

Microsoft Defender Hardening

The built-in endpoint protection platform was hardened to improve malware detection and prevention.

Configured features include:

Real-time malware protection

Cloud-delivered protection

Tamper protection

Automatic security intelligence updates

Threat history monitoring

These features improve protection against malware, ransomware, and other threats.

Firewall & Network Security

Network security was strengthened using Windows Defender Firewall.

Configuration steps:

Enabled firewall protection on all network profiles

Verified inbound firewall rules

Maintained default block inbound traffic policy

Reviewed application network permissions

This reduces exposure to unauthorized network connections.

Patch Management

Keeping systems updated is critical to mitigating vulnerabilities.

Actions taken:

Enabled automatic Windows Updates

Installed latest security patches

Verified Microsoft Defender definition updates

This ensures protection against known vulnerabilities.

Application & Execution Control

Software installation and execution were controlled to reduce malware risk.

Steps included:

Removing unnecessary applications

Restricting software installations to trusted sources

Enabling Microsoft SmartScreen

Practicing controlled software management

This helps prevent malicious software from executing on the system.

Browser Security

Web browsing is a common attack vector, so additional protections were enabled.

Security measures included:

Enabled tracking prevention

Limited browser extensions

Ensured browser remained fully updated

Practiced secure browsing habits

Removable Media Security

External devices can introduce malware or unauthorized data access.

Mitigation steps:

Practiced safe USB device usage

Avoided unknown external storage devices

Used USB data blockers when appropriate

This helps reduce the risk of BadUSB-style attacks.

Monitoring & Logging

Basic system monitoring was implemented to improve visibility into security events.

Monitoring tasks included:

Reviewing Windows Event Logs

Checking authentication events

Monitoring Microsoft Defender alerts

Verifying system protection status

This improves awareness of potential suspicious activity.

Project Outcome

After implementing these security controls, the Windows 11 system achieved a significantly improved security posture through:

Reduced attack surface

Stronger authentication practices

Encrypted storage

Active malware protection

Firewall-based network protection

Continuous system updates

Basic security monitoring

This project demonstrates hands-on experience with endpoint security and system hardening techniques commonly used in enterprise environments.

Skills Demonstrated

Endpoint Security

Operating System Hardening

Windows Security Configuration

Least Privilege Implementation

Disk Encryption (BitLocker)

Firewall Configuration

Security Monitoring

Defensive Cybersecurity Practices

Future Improvements

Potential future enhancements to this project include:

Implementing PowerShell-based hardening scripts

Applying CIS Benchmark configurations

Testing with security auditing tools

Implementing application whitelisting

Creating a home SOC monitoring lab

Author

Cybersecurity student with a focus on endpoint security, system defense, and practical security implementations.

## Screenshots

### Microsoft Defender Status
<img width="1365" height="720" alt="image" src="https://github.com/user-attachments/assets/cab7cc14-9593-4941-9967-751e8ae9d54b" />


### BitLocker Encryption Enabled
<img width="1123" height="590" alt="image" src="https://github.com/user-attachments/assets/a8a1f6e3-1d5f-47a8-81a4-d1f42bd37679" />


### Windows Firewall Configuration
<img width="1365" height="719" alt="image" src="https://github.com/user-attachments/assets/1b53d3c4-c277-46d1-819a-bfb97c8ce18e" />


### Windows Event Logs
![Event Logs](screenshots/event-logs.png)
