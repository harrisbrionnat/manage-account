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




<p>
  <h3
    <b> Disabling a User Account</b>
  </h3>
  <br>
  <br>
Navigate to <b>Active Directory Users and Computers<b/>. Right click the domain. Click 'Find'. Type in the name of a user. Right-click the user and click 'disable account'.
   <p>
<img src="https://imgur.com/UrDI5XU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

  <br>
  <p>
  <h3
    <b> Reset a User's Password</b>
  </h3>
  <br>
  <br>
Navigate to <b>Active Directory Users and Computers<b/>. Right click the domain. Click 'Find'. Type in the name of a user. Right-click the user and click 'reset password'.
   <p>
<img src="https://imgur.com/HZlmray.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

  <br>
  <p>
  <h3
    <b> Set up an account lockout policy using Group Policy</b>
  </h3>
  <br>
  <br>
Navigate to the Group Policy Management Console. Right click Start click 'Run' type gpmc.msc. Right click the domain and click 'Create a GPO in this domain, and Link it here. Name the GPO 'Account Lockout Policy'.
   <p>
<img src="https://imgur.com/vcmFdwD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Right clock the GPO and select 'Edit. On the GP Management Editor, go to <b>Computer Configuration</b>---> <b>Policies</b>---><b>Windows Settings</b>--><b>Security Settings</b>---><b>Account Policies</b>---><b>Account Lockout Policy</b>. Go to 'Account lockout Threshold' and set it to 3.
 <p>
<img src="https://imgur.com/ZGe9nrj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
