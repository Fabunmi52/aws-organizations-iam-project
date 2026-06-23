# AWS Organizations & IAM Access Management Project

## Overview
This project demonstrates how to implement a secure multi-account AWS environment using AWS Organizations and IAM.
The goal was to understand centralized governance, identity management, and role-based access control in AWS.

## Architecture Diagram

<img width="1536" height="1024" alt="ChatGPT Image Jun 23, 2026, 05_49_04 AM" src="https://github.com/user-attachments/assets/e460319a-577a-4c55-9d84-aeb3456b657d" />

## Technologies Used

- AWS Organizations
- IAM
- IAM Policies
- IAM Groups
- AWS Management Console

## Project Objectives
- Create multiple AWS accounts
- Implement RBAC
- Configure IAM Policies
- Apply Least Privilege
- Improve Cloud Governance


### Implementation Steps

### Step 1: Create AWS Organization

1. Sign into AWS Management Account
2. Enable AWS Organizations
3. Create Development Account
4. Create Testing Account
5. Create Production Account

### Step 1: IAM Groups

Developers
Testers
Admins
Auditors

### Step 1: Permissions

| Group      | Permissions |
| ---------- | ----------- |
| Developers | EC2, S3     |
| Testers    | Read-only   |
| Admins     | Full Access |
| Auditors   | Read-only   |


## Challenges

Challenge:
Understanding Service Control Policies (SCPs)

Solution:
Reviewed AWS documentation and tested SCP restrictions in a sandbox environment.

## Lessons Learned

- Importance of IAM
- Multi-account best practices
- RBAC implementation
- Cloud governance principles

  ## Future Enhancements

- Implement IAM Identity Center
- Configure SCPs
- Integrate AWS Config
- Automate setup with Terraform
