<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Resetting Passwords and Disabling, Deleting, and Unlocking Accounts</h1>
This tutorial outlines how one would disable user accounts, reset a user's password and observe logs within Active Directory.<br />




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
- Delete a user's account
- Unlock a user's account




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
   <br>
  <p>
  <h3
    <b> Delete a User's Password</b>
  </h3>
  <br>
  <br>
Navigate to <b>Active Directory Users and Computers<b/>. Right click the domain. Click 'Find'. Type in the name of a user. Right-click the user and click 'delete'.
   <p>
<img src="https://imgur.com/OmSKun5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

  <h3
    <b> Delete a User's Password</b>
  </h3>
  <br>
  <br>
Attempt to login into a user's account with the wrong password 4 times. The account will become locked. Log into an admin account. Go to the domain controller and log in as an admin. Go to Active Directory Users and Computers. on the domain, right click and select 'Find. Type in the user's name, Right click on 'Properties' check the box to unlock the account.
   <p>
<img src="https://imgur.com/mlu3NSR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

  <br>
  <p>
   
 
   
 
