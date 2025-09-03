# AZ-104 Lab 02a – Manage Subscriptions and RBAC

## 🧠 Overview
This lab demonstrates how to implement role-based access control (RBAC) and subscription management in Microsoft Azure. It covers the creation of management groups, assignment of built-in roles, creation of custom roles, and monitoring of role assignments using the Activity Log.

## 🎯 Objectives
- Create and configure Azure Management Groups
- Assign built-in roles (VM Contributor) to a Help Desk group
- Design and implement a custom RBAC role with scoped permissions
- Monitor role assignments using Azure Activity Log

## 🛠️ Tools & Services
- Azure Portal
- Microsoft Entra ID
- Azure Resource Manager (ARM)
- Role-Based Access Control (RBAC)

## 📸 Screenshots
Screenshots are included in the `/screenshots` folder, with sensitive information redacted. Key stages documented:
- Management group creation
- Role assignment (built-in and custom)
- Activity log filtering

## 🧩 Custom Role Summary
**Name**: `Custom Support Request`  
**Cloned From**: `Support Request Contributor`  
**Excluded Permission**: `Microsoft.Support/register/action`  
**Scope**: `az104-mg1` Management Group  
**Purpose**: Enforce least privilege for Help Desk support ticket creation

## 🔍 Reflection
This lab reinforced key concepts around RBAC inheritance, least privilege design, and Azure governance. Creating a custom role helped refine permission boundaries and highlighted the importance of scoped access in multi-subscription environments.

## 🚀 Next Steps
- Automate role assignments using Azure CLI or Bicep
- Extend RBAC strategy to include Azure Policy
- Integrate with identity governance workflows
# Manage-Subscriptions-and-RBAC-Project-2
Practical implementation of Azure RBAC and subscription management for AZ-104 certification
