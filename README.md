# Active Directory Security Simulation  

## Objective  
The **Active Directory Security Simulation** project was designed to **establish a controlled AD environment** for testing **brute-force attacks, privilege escalation, and log monitoring**. The primary goal was to **analyze security logs, detect threats, and implement security measures** within an AD infrastructure.  

### Skills Learned  

- Configuring **Active Directory Domain Services (ADDS)** for multi-user authentication  
- Implementing **Group Policy Objects (GPOs)** for security enforcement  
- Deploying **Splunk & Sysmon** for log monitoring and threat detection  
- Conducting **brute-force attack simulations** using **Kali Linux**  
- Understanding **event log analysis and SIEM integration**  
- Strengthening security through **privilege escalation detection**  

### Tools Used  

- **Windows Server 2022** – Active Directory & Group Policy setup  
- **Splunk & Sysmon** – Log collection, analysis, and real-time monitoring  
- **Windows Event Viewer** – Security log analysis  
- **Kali Linux** – Simulated attack testing (brute force, enumeration)  
- **PowerShell & CMD** – AD automation and security policy enforcement  

## Steps  

### **1. Active Directory Setup**  
- Installed **Windows Server 2022** and configured **Active Directory Domain Services (ADDS)**  
- Created **organizational units (OUs), users, and security groups**  
- Implemented **Group Policy Objects (GPOs)** for security hardening  
 

### **2. SIEM & Log Monitoring**  
- Installed **Splunk Universal Forwarder** for log ingestion  
- Deployed **Sysmon** to capture detailed event logs  
- Configured **Windows Event Viewer** for auditing security events  
  

### **3. Simulated Attack & Detection**  
- Performed **brute-force attack simulations** using **Hydra** on a test AD account  
- Monitored **failed login attempts and lockout events** in logs  
- Identified **privilege escalation attempts** using **Windows Event ID tracking**  


### **4. Security Analysis & Mitigation**  
- Implemented **account lockout policies** to prevent brute-force attacks  
- Restricted **PowerShell script execution** to reduce attack surface  
- Analyzed **Windows Event Logs & Splunk SIEM alerts** to detect suspicious activities  


