<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
  <img src="https://github.com/user-attachments/assets/382d1a52-9e22-48e3-aebb-47eb18087084"/>
  <img src="https://github.com/user-attachments/assets/829ef3bc-fe29-4910-9031-ff2e2549fcff"/>
<img src="https://github.com/user-attachments/assets/26e9a0bb-4cea-40b0-b18b-16a65cde5391"/>
  <img src="https://github.com/user-attachments/assets/b4fbdf0b-db15-4286-8a11-0c405c65c3b6"/>
</p>
<p>
Create a resource group in Microsoft Azure. Under the resource group creawte a Virtual Network and Subnet. We will create the Domain Controller virtual machine (Windows Server 2022). Afterwards we will log into the VM and disable Windows Firewall for testing. Once this is done, we will return to Azure and create a Client virtual machine and attach it to the same region and virual network as the Domain Controller. Set this VM's DNS settings to the Domain Controller's Private IP address.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/62632b3b-bb92-4bd8-ae1f-9084b3130c29"/>
</p>
<p>
Once you are logged into the Client VM attempt to ping the Domain Controller's  private IP address. Once the ping has succeeded run a ipconfig /all in PowerShell.
</p>
<br />

