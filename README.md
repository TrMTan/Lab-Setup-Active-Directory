# Lab-Setup-Active-Directory
This is a script to create vulnerable active directory that's allowing you to test most of active directory attacks in local lab

How to use
- Script was tested in Windows Server 2019
- You need to make your Windows Server to be DC
- You need install ADCS, module ADCSTemplate  
- You need run the script in DC with Active Directory installed
- Download file and save to file ps1 and run by administrator in powershell

Supported Attacks
- Kerberoasting
- AS-REP Roasting
- DCSync
- Golden Ticket
- ESC1
- Shadow Credentials
- Resource Based Constrained Delegation
- Abusing AD-DACL: ForceChangePassword
- Abusing AD-DACL: WriteOwner (User/Group)
- Anonymous LDAP

I will update another attacks soon 🥑
