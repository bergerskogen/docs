---
title: Defining security using Genus App Platform
description: How to define a security model using Genus Studio
author: OleGrytdal
---
# Security

A successful application must ensure that only properly authenticated users can sign in to the application, and that application resources (data and functions) is available only to authorized users. User authentication confirms the identity of any user trying to sign in to an application and lets users access application resources. User authorization secures resources from unauthorized access. After a user account has received authentication and can potentially access an object, the type of access actually granted is determined by what [privileges](security-privileges.md) are assigned to the user and which [permissions](security-permissions.md) are attached to the objects the user wants to access.

The security services provided by Genus App Platform are based on MicrosoftB. Active Directory mechanisms, and may optionally be integrated with an Active Directory-based domain controller.

**Topics in Security**
* [Account Profiles](account-profiles.md)
* [Security Groups and User Accounts](security-groups-and-user-accounts.md)
* [Sign in History](sign-in-history.md)
* [Security Permissions](security-permissions.md)
* [Security Privileges](security-privileges.md)
* [Security Data Sets](security-data-sets.md)
* [Security overview and review](security-overview-and-review.md)
* [Trusted Users](trusted-users.md)
