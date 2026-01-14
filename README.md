
# Password Reset

![image alt](https://github.com/DevinHarvinIT/Active-Directory-password-reset/blob/9085155f694cd4b7e6287810b0e1fc8206536406/images/AD%20Lab%20thumbnail.webp)

This lab demonstrates how to locate a user account and reset a password using Active Directory Users and Computers in a domain environment.

---

## Environments and Technologies Used

- Active Directory Users and Computers
- Windows Server
- Domain Controller
- Administrative Tools (Server Manager)

---

## Operating Systems Used

- Windows Server (Domain Controller)

---

## Summary of Steps

- Open Active Directory Users and Computers
- Locate the domain and user account
- Search for the target user
- Reset the user password
- Configure password reset options

---

## Step 1

![image alt](images/shot-1.png)](https://github.com/DevinHarvinIT/Active-Directory-password-reset/blob/92bbd87b91179786780ec9f2c615b0eb3a4eec0a/images/Shot%201.png)
![image alt](images/shot-2.png)](https://github.com/DevinHarvinIT/Active-Directory-password-reset/blob/92bbd87b91179786780ec9f2c615b0eb3a4eec0a/images/Shot%202.png)

<p align="center"><b>OPENING ACTIVE DIRECTORY USERS AND COMPUTERS</b></p>

Active Directory Users and Computers is accessed from the server to begin user account management.

Navigation path used:
Server Manager → Tools → Active Directory Users and Computers

---

## Step 2

![image alt](images/shot-3.png)](https://github.com/DevinHarvinIT/Active-Directory-password-reset/blob/92bbd87b91179786780ec9f2c615b0eb3a4eec0a/images/Shot%203.png)
![image alt](images/shot-4.png)](https://github.com/DevinHarvinIT/Active-Directory-password-reset/blob/92bbd87b91179786780ec9f2c615b0eb3a4eec0a/images/Shot%204.png)

<p align="center"><b>LOCATING THE USER ACCOUNT IN THE DOMAIN</b></p>

The domain container (house icon) represents the Active Directory domain where user accounts are stored. The Find feature is used to quickly locate the target user.

Navigation path used:
Right-click domain → Find → Enter user name

---

## Step 3

![image alt](images/shot-5.png)](https://github.com/DevinHarvinIT/Active-Directory-password-reset/blob/92bbd87b91179786780ec9f2c615b0eb3a4eec0a/images/Shot%205.png)

<p align="center"><b>INITIATING PASSWORD RESET</b></p>

Once the correct user account is identified, the password reset option is accessed from the context menu.

Navigation path used:
Right-click user account → Reset Password

---

## Step 4

![image alt](images/shot-6.png)](https://github.com/DevinHarvinIT/Active-Directory-password-reset/blob/92bbd87b91179786780ec9f2c615b0eb3a4eec0a/images/Shot%206.png)
![image alt](images/shot-7.png)](https://github.com/DevinHarvinIT/Active-Directory-password-reset/blob/92bbd87b91179786780ec9f2c615b0eb3a4eec0a/images/Shot%207.png)

<p align="center"><b>PASSWORD RESET CONFIGURATION</b></p>

The password reset dialog allows the administrator to define a new password and apply account options.

Actions performed:
- Enter and confirm a new password
- Select User must change password at next logon
- Select Unlock the user’s account (if applicable)
- Apply changes

---

## Result

The user password was successfully reset, and account access settings were updated. The user can authenticate using the new credentials based on the selected options.
