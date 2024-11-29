# Active Directory Setup and Configuration Project

This project demonstrates the setup and management of an **Active Directory (AD)** environment using **Windows Server** and **Windows Client** systems in a virtualized environment. The focus is on creating a simulated enterprise network to manage users, groups, policies, and shared resources effectively.

---

## Project Overview

The goal of this project is to showcase the configuration and management of an Active Directory environment, including organizational units, user and group management, group policy implementation, and network resource sharing. It is designed to replicate a real-world enterprise setup for learning and demonstration purposes.

---

## Features Implemented

### 1. **Active Directory Configuration**
- Configured a domain controller on a Windows Server virtual machine.
- Created and managed **Organizational Units (OUs)** for departments:
  - IT Department
  - Finance Department
  - HR Department

### 2. **User and Group Management**
- Created users using both **manual** and **copy** methods.
- Assigned users to their respective OUs.
- Configured user properties, including roles and managers.
- Created department-specific groups and added members:
  - IT Group
  - Finance Group
  - HR Group

### 3. **Group Policy Implementation**
- Applied policies for security and user experience:
  - Account Lockout Policy
  - Password Policy
  - CMD Disable Policy (to prevent unauthorized command-line access)
  - Desktop Wallpaper Policy (department-specific, with restrictions on changing backgrounds)

### 4. **Shared Resources**
- Created shared drives for each department:
  - IT Share
  - Finance Share
  - HR Share
- Configured access permissions to ensure appropriate access control.

### 5. **Client Integration**
- Joined Windows Client machines to the domain.
- Verified user access and group policy enforcement.
- Mapped network drives on client systems for shared resource access.

---

## Tools and Technologies

1. **Virtual Machines (VirtualBox):** 
   Used to create isolated environments for Windows Server and Client systems.

2. **Windows Server:** 
   Served as the domain controller to configure and manage the Active Directory environment.

3. **Windows Clients (Windows 10/11):** 
   Acted as client devices joined to the domain for testing and demonstration.

4. **CherryTree:** 
   Utilized for documenting processes, configurations, and observations.

5. **Greenshot:** 
   Used to capture screenshots for visual documentation.

---

## Project Workflow

1. **Setting up Virtual Machines:**
   - Installed and configured Windows Server as the domain controller.
   - Installed Windows Client systems and joined them to the domain.

2. **Active Directory Management:**
   - Created OUs, users, and groups for organizational management.
   - Configured user attributes and assigned managers.

3. **Policy Implementation:**
   - Configured and enforced security policies using Group Policy Management.

4. **Shared Resources:**
   - Created shared drives for each department and assigned appropriate permissions.

5. **Verification:**
   - Verified policy application and shared resource access on client systems.

---

## Recommendations for Future Enhancements

- Explore advanced Group Policies for software deployment and user environment customization.
- Implement and test replication of Active Directory across multiple domain controllers.
- Configure more advanced security measures, such as auditing and conditional access policies.
- Expand the network to include additional services like DNS, DHCP, and Certificate Authority.

---

## Project Outcomes

This project demonstrates a foundational understanding of Active Directory setup and management, including user and group management, policy enforcement, and resource sharing. It serves as a practical learning experience for IT professionals working with enterprise networks.

---

## How to Use

1. Clone this repository to view project files and documentation:
   ```bash
   git clone https://github.com/dawishcyber/Active-Directory-Project.git
2. Follow the documentation to replicate the setup in your virtual environment.


