# Installing Active Directory
Comprehensive Guide to Installing and Configuring Active Directory Domain Services on Windows Server 2022

## Part 1: Initializing the Configuration

### 1. Welcome to Server Manager
![Welcome to Server Manager](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_01.png?raw=true)
*The Server Manager Dashboard - your centralized console for managing server roles and features. Select option 2: "Add roles and features".*

### 2. Choosing the Installation Type
![Select Installation Type](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_02.png?raw=true)
*Select 'Role-based or feature-based installation' to proceed.*

### 3. Server Selection for Role Installation
![Server Selection](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_03.png?raw=true)
*Here's where you'll find prompts for post-deployment tasksSelecting the destination server for role installation in the Add Roles and Features Wizard on Windows Server 2022. Click 'Next' to continue.*

### 4. Selecting Server Roles
![Selecting Server Roles](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_04.png?raw=true)
*Choose 'Active Directory Domain Services' from the list of roles to install on your server. Once selected, additional features required for AD DS will also be installed.*

## Part 2: Select Server Roles and Confirm Installation

After selecting the server, you will choose the roles to install. For Active Directory Domain Services:

1. Check the box next to "Active Directory Domain Services".
2. Additional features required for AD DS will be automatically selected. Click "Add Features".

   ![Select Server Roles](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_05.png?raw=true)

3. After adding features, click "Next" to review your selections. Then click "Install" to start the installation process. You will see the progress bar indicating the installation status.

   ![Installation Progress](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_06.png?raw=true)

*Ensure you have all necessary roles and features checked before proceeding with the installation.*

### 3. Access Notifications for Post-Deployment Configuration
![Server Manager Notifications](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_07.png?raw=true)
*Once the role and features are installed, access the notifications area in 'Server Manager' to promote the server to a domain controller.*

### 4. Promote Server to a Domain Controller
![Promote to Domain Controller](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_08.png?raw=true)
*From the notifications area, select 'Promote this server to a domain controller' to begin post-deployment configuration.*

## Part 3: Domain Controller Promotion

### 1. Specifying Domain Information
![Deployment Configuration](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_09.png?raw=true)
*Enter the desired root domain name for your new forest. This will be the foundation of your Active Directory structure.*

### 2. Configuring NetBIOS Name
![Additional Options](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_10.png?raw=true)
*Confirm the NetBIOS name, which provides compatibility with network clients and services that use an older naming convention.*

### 3. Reviewing Your Options
![Review Options](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_11.png?raw=true)
*Review all selected options for the new domain before proceeding to ensure all configurations are correct.*

### 4. Pre-requisites Check
![Prerequisites Check](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_12.png?raw=true)
*Before the installation begins, Windows will conduct a prerequisites check to ensure the server is ready for the AD DS role.*

### 5. Automatic Sign Out
![Automatic Sign Out](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_13.png?raw=true)
*Post-installation, the server needs to be rebooted. This prompt will automatically sign you out to complete the installation.*

### 6. Remote Desktop Disconnection
![Remote Desktop Disconnection](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_14.png?raw=true)
*Your Remote Desktop session will end because the server is restarting as part of the AD DS installation process.*

### 7. Reconnecting to Server
![Reconnecting to Server](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_15.png?raw=true)
*Once the server is back online, reconnect to your server with the domain credentials you just created.*

### 8. Certificate Warning
![Certificate Warning](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_16.png?raw=true)
*A security warning about the server's certificate may appear when you reconnect. This is common in new setups without a verified certificate.*

## Part 4: Post-Restart Verification

### Accessing Active Directory Tools
![Server Manager with AD DS](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_17.png?raw=true)
*Back in Server Manager, you can now access tools like Active Directory Users and Computers to manage your new domain.*


