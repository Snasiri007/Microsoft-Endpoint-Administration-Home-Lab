# Microsoft Endpoint Administration Home Lab

Hands-on lab focused on Windows administration, Microsoft Entra ID, identity and access management, PowerShell, troubleshooting, security, and endpoint administration.

## Lab Environment

- Windows 11 ARM virtual machine
- UTM virtualization on macOS
- Microsoft Entra ID
- Microsoft 365
- Microsoft Authenticator
- PowerShell

## Skills Demonstrated

- Windows 11 administration
- Local user and group management
- Password resets and account lockout troubleshooting
- Event Viewer and Windows Security logs
- Windows services and Device Manager
- PowerShell administration
- Network and DNS troubleshooting
- Group Policy and Local Security Policy
- Software installation and removal
- Microsoft Entra ID user and group administration
- Multi-Factor Authentication
- Microsoft Authenticator
- Sign-in and audit log investigation
- Session revocation
- Account enable/disable and recovery
- RBAC and least-privilege administration

## Lab Projects

### 01 - Windows User Administration
Created and managed local Windows users and groups, performed password resets, and tested account access.

### 02 - PowerShell Administration
Used PowerShell for Windows administration, system inspection, and troubleshooting.

### 03 - Account Lockout Troubleshooting
Created controlled authentication failures and used Windows logs to investigate failed sign-ins and account lockouts.

![Windows Security Event ID 4625 showing a failed login](screenshots/event-viewer-4625-failed-login.png)

*Verified failed authentication activity in the Windows Security log using Event ID 4625.*

![Windows Security Event ID 4740 showing an account lockout](screenshots/event-viewer-4740-account-lockout.jpg)

*Verified the locked account in the Windows Security log using Event ID 4740.*

### 04 - Event Viewer and Security Logs
Reviewed Windows Event Viewer and Security logs to identify authentication and account-related events.

### 05 - Network Troubleshooting
Used PowerShell tools to inspect network adapters, IP configuration, connectivity, and DNS resolution.

### 06 - Group Policy and Local Security Policy
Configured and tested Windows security and policy settings in a lab environment.

### 07 - Software Management
Installed, verified, and removed software as part of endpoint lifecycle testing.

### 08 - Microsoft Entra ID Administration
Created cloud users and security groups and managed group membership.

![Microsoft Entra security group membership](screenshots/entra-security-group-membership.png)

*Verified LAB User 1 as a direct member of the LAB-HelpDesk security group.*

### 09 - MFA and Authentication
Configured MFA with Microsoft Authenticator and tested authentication workflows.

![Microsoft Authenticator MFA registration](screenshots/entra-mfa-authenticator.png)

*Verified Microsoft Authenticator as a registered push-based multi-factor authentication method.*

### 10 - Sign-in and Audit Logs
Reviewed Microsoft Entra sign-in and audit logs to investigate authentication activity.

![Microsoft Entra sign-in logs](screenshots/entra-signin-logs.png)

*Reviewed interactive sign-in activity to verify successful authentication and investigate sign-in behavior.*

### 11 - Password Reset and Session Revocation
Reset cloud-user passwords, forced password changes, revoked active sessions, and verified reauthentication.

![Microsoft Entra password and session audit activity](screenshots/entra-password-session-audit.png)

*Used Entra audit logs to verify password-reset, password-change, and session-related administrative activity.*

### 12 - Account Access Recovery
Disabled a user account, reproduced the access failure, re-enabled the account, and verified successful recovery.

### 13 - RBAC and Least Privilege
Assigned a temporary Helpdesk Administrator role, tested administrative access, and removed the role after validation.

![Helpdesk Administrator role assigned](screenshots/entra-helpdesk-role-assigned.png)

*Temporarily assigned the Helpdesk Administrator role to test delegated administrative access.*

![Helpdesk Administrator role removed](screenshots/entra-helpdesk-role-removed.png)

*Removed the privileged role after testing and verified that no directory roles remained assigned.*

## Intune

**Status: In Progress**

Planned labs:

- Windows device enrollment
- Device inventory
- Configuration profiles
- Compliance policies
- Application deployment
- Windows update rings
- Endpoint security
- Policy and application troubleshooting

## Objective

Build practical hands-on experience in Microsoft endpoint administration, identity and access management, security, and troubleshooting using Windows, Microsoft Entra ID, PowerShell, and Intune while preparing for MD-102 and future cloud administration roles.
