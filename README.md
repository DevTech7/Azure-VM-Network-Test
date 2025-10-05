# Azure Virtual Machine Deployment and Network Connectivity Test

## Project Summary
This project demonstrates the deployment of a Windows 10 Virtual Machine in Microsoft Azure and the validation of its connectivity through Remote Desktop Protocol (RDP) and network diagnostic commands such as `ipconfig` and `ping`.

The goal is to showcase practical skills in setting up cloud infrastructure, configuring secure remote access, and confirming system functionality through network testing. This hands-on project highlights foundational cloud engineering and troubleshooting techniques relevant to IT and DevOps roles.

---

## Languages and Tools Used
- Microsoft Azure
- Windows 10 VM
- Remote Desktop Protocol (RDP)
- PowerShell / Command Prompt

---

## Environments
- Azure Cloud Environment
- Windows 10 Virtual Machine

---

## Steps Demonstrated
1. Resource Group creation in Azure
2. Virtual Machine deployment with configuration
3. Remote Desktop login
4. Network configuration test with `ipconfig`
5. Connectivity test using `ping 8.8.8.8`

---

## Screenshots

## Screenshots

### 1. Azure Resource Group Overview  
![Resource Group Overview](images/Resource%20Group%20Overview.png)  
*This screenshot shows the newly created resource group in the Azure portal, confirming its successful deployment and location settings.*

---

### 2. Virtual Network Overview  
![Virtual Network Overview](images/Virtual%20Network%20Overview.png)  
*Displays the configured virtual network (VNet) and its subnet details, ensuring logical network isolation and proper address range setup.*

---

### 3. VM Validation  
![VM Validation](images/VM%20Validation.png)  
*Shows successful validation of all virtual machine settings before deployment, including size, region, and credentials.*

---

### 4. VM Deployment  
![VM Deployment](images/VM%20Deployment.png)  
*Demonstrates that the VM has been successfully deployed with its assigned configuration, confirming completion of provisioning.*

---

### 5. VM Overview with Public Address  
![VM Overview with Public Address](images/VM%20Overview%20with%20public%20address.png)  
*Displays the VM overview page, including the assigned public IP address used for RDP connectivity.*

---

### 6. RDP Setup  
![RDP Setup](images/RDP%20Setup.png)  
*Shows configuration of Remote Desktop Protocol (RDP) settings and the security warning prior to login.*

---

### 7. RDP Connection to VM  
![RDP Connection to VM](images/RDP%20connection%20to%20VM.png)  
*Confirms a successful RDP session to the virtual machine, indicating external connectivity is working.*

---

### 8. IP Configuration Output  
![IP Configuration Output](images/Ipconfig%20Output%20.png)  
*Command prompt output from `ipconfig`, confirming the internal IP address and adapter configuration of the VM.*

---

### 9. Ping Connectivity Test  
![Ping Test](images/ping%208.8.8.8%20-n-%204%20.png)  
*Validates internet connectivity by successfully pinging Google’s DNS (8.8.8.8) with four reply responses.*


## Demonstration
This project illustrates how to:
- Deploy a Virtual Machine in Azure
- Connect securely using RDP
- Run basic network troubleshooting commands to confirm system functionality
