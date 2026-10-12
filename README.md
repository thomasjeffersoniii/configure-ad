# configure-ad<p align="center">
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
- Windows 11 (22H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img  <img width="1892" height="994" alt="Screenshot 2026-09-22 115245" src="https://github.com/user-attachments/assets/475a3335-def7-4027-ad3e-c819b5bf96c1" 


</p>
<p>

Configured the mydomain.com Active Directory domain and created dedicated organizational units for administrators, employees, and client computers. The jane_admin account was configured as a Domain Administrator, while user and computer accounts were organized within their respective OUs.
</p>
<br />

<p>
<img <img width="1818" height="999" alt="Screenshot 2026-09-22 114859" src="https://github.com/user-attachments/assets/ea7853a4-d6ec-484f-81c0-e33b1c8cb977" />

</p>
<p>
Verified that Client-1 successfully authenticates users against the mydomain.com Active Directory domain. Remote Desktop access was configured to allow standard Domain Users to connect without requiring administrative privileges.
</p>
<br />

<p>
<img <img width="1877" height="1009" alt="Screenshot 2026-10-08 013544" src="https://github.com/user-attachments/assets/c5801dfd-7e2f-4d03-a5bc-8ea85272d73b" />

</p>
<p>
Configured an Active Directory Group Policy to lock user accounts after five unsuccessful authentication attempts. The policy was tested by intentionally entering an incorrect password and verifying the resulting account lockout before restoring access.
</p>
<br />
