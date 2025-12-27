# AWS IAM Basics (Beginner Notes)

IAM stands for Identity and Access Management.
It is used to control who can access AWS resources and what actions they can perform.

## What IAM is used for
- Creating users
- Creating groups
- Assigning permissions
- Controlling access securely

## IAM Users
An IAM user represents a person or service that needs access to AWS.
Each user has:
- A username
- Credentials (password or access keys)

## IAM Groups
Groups are collections of users.
Permissions are assigned to groups instead of individual users.

Example:
- Developer group
- Admin group
- ReadOnly group

## IAM Policies
Policies are written in JSON.
They define what actions are allowed or denied.

Example:
- Allow EC2 read access
- Deny S3 delete access

## Important Points
- IAM is a global service
- By default, everything is denied
- Always follow least privilege principle

## My Understanding
IAM is confusing at first, but it makes sense once I understand
that users and groups do nothing without policies.
