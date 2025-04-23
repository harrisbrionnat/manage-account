
   <p align="center">
    <img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

# Resetting Passwords and Disabling, Deleting, and Unlocking Accounts
This tutorial outlines how to disable user accounts, reset a user's password, and observe logs within Active Directory.

## Environments and Technologies Used
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services

## Operating Systems Used 
- Windows Server 2022
- Windows 10 (21H2)

## High-Level Configuration Steps
- Disable a user's account
- Reset a user's password
- Delete a user's account
- Unlock a user's account

### Disabling a User Account
<p>
Navigate to <b>Active Directory Users and Computers</b>. 
1. Right-click the domain.
2. Click **Find**. 
3. Type the name of the user.
4. Right-click the user and click **Disable Account**.
</p>
<p>
    <img src="https://imgur.com/UrDI5XU.png" height="80%" width="80%" alt="Disable User Account"/>
</p>

### Reset a User's Password
<p>
Navigate to <b>Active Directory Users and Computers</b>.
1. Right-click the domain.
2. Click **Find**.
3. Type the name of the user.
4. Right-click the user and click **Reset Password**.
</p>
<p>
    <img src="https://imgur.com/HZlmray.png" height="80%" width="80%" alt="Reset User Password"/>
</p>

### Delete a User's Account
<p>
Navigate to <b>Active Directory Users and Computers</b>.
1. Right-click the domain.
2. Click **Find**.
3. Type the name of the user.
4. Right-click the user and click **Delete**.
</p>
<p>
    <img src="https://imgur.com/OmSKun5.png" height="80%" width="80%" alt="Delete User Account"/>
</p>

### Unlock a User's Account
<p>
1. Attempt to log into a user's account with the wrong password 4 times. 
2. The account will become locked. 
3. Log into an admin account.
4. Go to the domain controller and log in as an admin.
5. In **Active Directory Users and Computers**, right-click the domain and select **Find**.
6. Type in the user's name, right-click on the user, go to **Properties**, and check the box to unlock the account.
</p>
<p>
    <img src="https://imgur.com/mlu3NSR.png" height="80%" width="80%" alt="Unlock User Account"/>
</p>

 
   
 
