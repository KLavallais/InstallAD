# InstallAD
Comprehensive Guide to Installing and Configuring Active Directory Domain Services on Windows Server 2022

## Part 1: Initializing the Configuration

### 1. Welcome to Server Manager
![Welcome to Server Manager](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_01.png?raw=true)
*The Server Manager Dashboard - your centralized console for managing server roles and features.*

### 2. Choosing the Installation Type
![Select Installation Type](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_02.png?raw=true)
*Select 'Role-based or feature-based installation' to proceed.*

### 3. Server Manager Notifications
![Server Manager Notifications](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_03.png?raw=true)
*Notifications alert you to important actions. Here's where you'll find prompts for post-deployment tasks.*

### 4. Promoting a Server to a Domain Controller
![Promoting to Domain Controller](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_04.png?raw=true)
*After adding roles, you'll receive a notification to promote your server to a domain controller.*

## Part 2: Adding Roles and Features

### 5. The Add Roles and Features Wizard
![Add Roles and Features Wizard](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_05.png?raw=true)
*The Add Roles and Features Wizard is where you'll begin adding new functions to your server.*

### 6. Selecting a Destination Server
![Selecting Destination Server](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_06.png?raw=true)
*Choose a server from the server pool to install the Active Directory role.*

### 7. Choosing Active Directory Domain Services
![Choosing AD Domain Services](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_07.png?raw=true)
*Check 'Active Directory Domain Services' to install the necessary AD DS role.*

### 8. Confirming Required Features
![Confirming Required Features](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_08.png?raw=true)
*Confirm the additional features required for AD DS to function properly.*

## Part 3: Domain Controller Promotion

### 9. Specifying Domain Information
![Deployment Configuration](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_09.png?raw=true)
*Enter the desired root domain name for your new forest. This will be the foundation of your Active Directory structure.*

### 10. Configuring NetBIOS Name
![Additional Options](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_10.png?raw=true)
*Confirm the NetBIOS name, which provides compatibility with network clients and services that use an older naming convention.*

### 11. Reviewing Your Options
![Review Options](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_11.png?raw=true)
*Review all selected options for the new domain before proceeding to ensure all configurations are correct.*

### 12. Pre-requisites Check
![Prerequisites Check](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_12.png?raw=true)
*Before the installation begins, Windows will conduct a prerequisites check to ensure the server is ready for the AD DS role.*

### 13. Automatic Sign Out
![Automatic Sign Out](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_13.png?raw=true)
*Post-installation, the server needs to be rebooted. This prompt will automatically sign you out to complete the installation.*

### 14. Remote Desktop Disconnection
![Remote Desktop Disconnection](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_14.png?raw=true)
*Your Remote Desktop session will end because the server is restarting as part of the AD DS installation process.*

### 15. Reconnecting to Server
![Reconnecting to Server](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_15.png?raw=true)
*Once the server is back online, reconnect to your server with the domain credentials you just created.*

### 16. Certificate Warning
![Certificate Warning](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_16.png?raw=true)
*A security warning about the server's certificate may appear when you reconnect. This is common in new setups without a verified certificate.*

## Part 4: Post-Restart Verification

### 17. Accessing Active Directory Tools
![Server Manager with AD DS](https://github.com/KLavallais/KLavallais/blob/main/images/Screenshot_17.png?raw=true)
*Back in Server Manager, you can now access tools like Active Directory Users and Computers to manage your new domain.*


