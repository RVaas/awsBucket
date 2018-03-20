---
layout: post
title:  
date:   2018-03-15 23:29:22 +0000
---
<a href="https://aws.amazon.com/iam/faqs/">IAM - Frequently asked questions</a>

IAM (Identity Access Management) essentially allows you to manage users, groups, roles and their corresponding level of access to the AWS Platform. It provides:

+ Centralized control of your AWS account
+ Shared access to your AWS Account
+ Granular Permissions
+ Identify Federation (including Active Directory, Facebook, Linkedin etc)
+ Multifactor Authentication
+ Provide temporary access for users/ devices and services where necessary
+ Allows you to set your own password rotation policy
+ Integrates with many AWS services
+ Supports PCI DSS Compliance

IAM Consists of:

+ **Users** 
+ **Groups** - A way to group users and apply policies to them collectively
+ **Roles** - Users can assume the role to which they are tagged, limited by the policies attached
+ **Policy** Documents - JSON format, key value pairs to define access permission on AWS Services

Points to note:

+ IAM is universal, not region specific. 
+ **Root Account** is simply the account created when your AWS account is created. Contains Administrator privileges
+ New Users have **NO** permissions when first created
+ New Users are assigned **ACCESS KEY ID & SECRET ACCESS KEYS** when first created. These cannot be used to login to the AWS Comsole, they can however be used to login to the command line
+ Always set up **Multi-factor Authentication** on root account
