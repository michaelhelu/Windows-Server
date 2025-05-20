### 🪟 Windows Server Project – `README.md`

```markdown
# Windows Server Virtual Lab Project

This project showcases enterprise-level Windows Server and domain management. It was completed using VirtualBox and includes Windows 10, Kali Linux, and Windows Server 2016 environments.

## 🛠️ Topics Covered

### 🖥️ VM Setup
- Installed Windows 10, Kali Linux, and Windows Server 2016
- Configured a NAT network and verified WAN connectivity

### ⚙️ Windows Server Configuration
- Renamed server to `Server20`
- Installed Active Directory Domain Services (ADDS)
- Promoted server to a domain controller

### 🧑‍💼 Domain Management
- Renamed Windows 10 client to `PC1` and joined domain
- Created organizational units: Developers, IT, QA, HR, Designers
- Added 5 users per OU and assigned to groups
- Promoted one user from each OU to Domain Admin

### 🌐 DNS & Group Policy
- Created DNS record for client machine (`Client-A`)
- Applied GPOs:
  - Custom wallpapers per department
  - Blocked Control Panel for QA users
  - Blocked CMD for HR users

### 🔐 Security Policies
- Enabled lockout after failed login attempts
- Admins can unlock accounts only

### 📁 Shared Drive
- Created a secure “Files” share for Developers & Designers only
