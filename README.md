<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Disabling Accounts, Resetting Passwords,Setting Account Lockout Policies and Observing Logs in Active Directory</h1>
This tutorial outlines how one would disable user accounts, reset a user's password, change and create user lockout policies, and observe logs within Active Directory.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services


<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Configuration Steps</h2>

- Disable a user's account
- Reset a user's password
- Create an account lockout policy
- Observe logs for Active Directory Users

  <h2>Deployment and Configuration Steps</h2>


<p>
  <h3
    ><b> Creating a 'Sales' Group</b>
  </h3>
  <br>
  <br>
1. Create an OU called 'Sales' in <b>Active Directory Users and Computers<b/>. Right click and click 'New' and choose 'Group'. Call the groups 'SalesGroup'. The scope will be 'Global and the type will be 'Security Groups'. Add some users to the OU 'Sales'.
   <p>
<img src="https://imgur.com/PU5Tohl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
     <p>
<img src="https://imgur.com/Te34GwC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  <br>
