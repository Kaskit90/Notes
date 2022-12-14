
# Manage Identities and Governance in Azure

These notes cover the Microsoft study material for the AZ-104 exam.

## Links

[Git Cheatsheet](git_notes.md)

[Types of users](https://learn.microsoft.com/en-us/training/modules/configure-user-group-accounts/2-create-user-accounts)
    - Types of user accts in Azure AD

[Types of Groups](https://learn.microsoft.com/en-us/training/modules/configure-user-group-accounts/5-create)
    - 3 different group types and reasons for use when creating accounts in Azure AD

[Azure Active Directory Interactive Walk Through](https://learn.microsoft.com/en-us/training/modules/configure-user-group-accounts/7-simulation-user-groups)
    - Walk through on setting up users and creating groups and tenants

## Module Description

In this module, you learned about Azure AD features and explored implementation scenarios. You reviewed the main components of Azure AD, including tenants, identities, and accounts, and learned how they're related. You compared Active Directory Domain Services to Azure AD, and discovered how different Azure AD editions support features. You explored the benefits of the Azure AD join and self-service password reset (SSPR) features, and considered how to implement them for your organization.

1. Gives users managed access to applications and files managed by Azure.
2. Active Directory self service password reset allows users to reset their own passwords. Must have valid license to use. Can reset passwords with email, text, or code. As well as with security questions. Must require one when setting up permissions.

### Knowledge Check

1. What correctly descripes Azure Active Directory?
    - Azure AD is primarily an identity solution.
2. What term defines a dedicated and trusted instance of Azure Active Directory?
    - Azure tenant
3. Your users want to sign-in to devices, apps, and services from anywhere. Users want to sign-in by using an organizational work or school account instead of a personal account. What should you do first?
    - Join the device to Azure AD.

## Configure user and group accounts

1. Type of acct determines where user is defined and whether the user is internal or external to Azure AD organization. [Types of users](https://learn.microsoft.com/en-us/training/modules/configure-user-group-accounts/2-create-user-accounts)

2. A user accont can not be restorred after being deleted if more than 30 days have passed.
3. Allows you to audit log information for user accts and collect sign in data.
4. Must be an admin to create or delete user accounts.
5. Results file in Azure portal will display the reason for each error such as duplicate accounts or already existing accounts.

### TYPES OF GROUP MEMBERS

[Things to consider](https://learn.microsoft.com/en-us/training/modules/configure-user-group-accounts/5-create)
    - What group types are for and who has permission to create said groups. How they are used.

[Azure Active Directory Interactive Walk Through](https://learn.microsoft.com/en-us/training/modules/configure-user-group-accounts/7-simulation-user-groups)
    - Walk through on setting up users and creating groups and tenants
  
[Lakeside Builders Active Directory](https://aad.portal.azure.com/#view/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/~/Overview)

### QUESTIONS FOR REVIEW

1. What type of user account allows an external organization to access your resourses?
   - Answer - A guest user account for each member of the external team. Access given with an existing email. Permissions are set up before the invitation to join group is sent.

2. What kind of group account can you creat so you can apply the same permissions to all group members?
   - Answer - Security Group. Only users with security permissions will have access to these groups.

3. Global administrator enables a user to manage all groups in you Teams tenants, and also assign other admin roles. You can not create accounts if you are not an admin account.

## SUMMARY

1. Azure Administrators must be familiar with configuring user and group accounts in Azure Active Directory.

In this module, you learned that every user who wants access to Azure resources needs an Azure user account. Azure AD supports access to your organization's resources by assigning access rights to users and groups. You discovered how user and group accounts are created in Azure AD. You explored how to configure and manage user and group accounts, including bulk configuration. You reviewed how your organization can support group account organization, and manage accounts across multiple directories.
