# Enterprise Identity & Access Management (IAM) Lab

## Project Overview

A hands-on Enterprise Identity and Access Management (IAM) project built using **Keycloak and Docker**.

The project simulates an enterprise environment for SecureTech Solutions to explore identity provisioning, department-based group management, Role-Based Access Control (RBAC), and access governance.

## Objectives

- Understand enterprise identity lifecycle management.
- Implement centralized identity administration.
- Configure department-based groups and roles.
- Apply Role-Based Access Control (RBAC).
- Explore the Principle of Least Privilege.
- Document access-control policies and IAM configurations.

## Technology Stack

- **Identity Provider:** Keycloak
- **Containerization:** Docker
- **Environment:** Windows with Docker Desktop
- **IAM Concepts:** Identity Provisioning, RBAC, Group Management, Role Mapping, Least Privilege

## Enterprise Environment

The simulated organization contains five departments:

| Department | Group | Role |
| HR | HR_Group | HR_Analyst |
| IT | IT_Group | IT_Support |
| Finance | Finance_Group | Finance_Analyst |
| Security | Security_Group | Security_Analyst |
| Marketing | Marketing_Group | Marketing_Editor |

## Implemented Features

### 1. Identity Provisioning
- Created five fictional employee accounts.
- Organized employees according to their departments.
- Configured department-based group membership.

### 2. Role-Based Access Control (RBAC)
- Created five department-specific realm roles.
- Mapped roles to corresponding department groups.
- Verified role inheritance through group membership.

### 3. Access Control Design
- Studying resource-level access requirements.
- Designing an Access Control Matrix based on least-privilege principles.

## Project Status

**Status: In Progress**

Upcoming implementation phases:

- Access Control Matrix documentation
- Authorization testing
- Multi-Factor Authentication (MFA)
- Joiner-Mover-Leaver (JML) lifecycle scenarios
- Access reviews and audit documentation

## Implementation Evidence

### 1. Department-Based Groups

Five department groups configured in the SecureTech realm.

![Department Groups](IAM%20Project%20ss1.png)

### 2. Realm Role Configuration

Five custom department roles created in Keycloak.

![Realm Roles](IAM%20project%20ss2.png)

## Learning Outcomes

This project provides practical exposure to identity administration, centralized access management, group-role mapping, RBAC configuration, and identity governance concepts.

## Disclaimer

This is an educational IAM lab using fictional employee identities and a local Keycloak development environment. It is not a production enterprise deployment. Actual application-level authorization enforcement is a separate implementation phase.
