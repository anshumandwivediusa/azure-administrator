# Azure Administrator Exam – AZ-104: Community Study Guide

This repository is a community-built study guide for anyone preparing for the Microsoft Azure Administrator Associate certification, specifically the AZ-104 exam. It brings together the core principles, operational practices, and design patterns needed to administer Azure environments with confidence.

Rather than simply collecting notes, this guide is built around practical cloud operations, decision-making under real constraints, and the habits of a strong Azure administrator. Each section pairs conceptual explanations with real-world implementation patterns so learners can understand not only what Azure does, but how and why administrators make certain choices in production.

## Core Concepts for Azure Administration

- **Identity is the foundation of trust**  
  In Azure, access control is not an afterthought — it is the control plane of the environment. Effective administration depends on understanding Azure Active Directory / Microsoft Entra ID, role assignment, least privilege, and how identity is enforced across subscriptions, resource groups, and services.

- **Availability is designed, not assumed**  
  A platform is only as reliable as the design decisions behind it. Azure administrators must think about redundancy, regional resilience, service health, resource limits, and recovery models. High availability is not just a feature; it is an operational architecture decision.

- **Networking is both connectivity and control**  
  Virtual networks, subnets, NSGs, route tables, load balancers, VPNs, and public IPs are not isolated topics — they form the foundation of how resources communicate and how security boundaries are enforced. Good Azure administration requires understanding how traffic flows, where it is filtered, and where trust is imposed.

- **Security is an operational discipline**  
  Azure administrators are responsible for more than provisioning resources. They must manage access, enforce policies, monitor configuration drift, and design secure patterns across identity, networking, storage, and compute. Security in Azure is a continuous practice, not a one-time configuration.

- **Governance shapes scale**  
  As environments grow, governance becomes essential. Proper use of management groups, policies, tags, RBAC, and cost management controls helps administrators keep the environment consistent, compliant, and manageable. Governance is how Azure estates remain stable under change.

- **Automation reduces operational risk**  
  Azure environments are rarely static. Repetitive tasks, configuration drift, and scaling events create risk when handled manually. Automation through Azure CLI, PowerShell, ARM/Bicep, and Azure-native tooling helps make operations repeatable, auditable, and resilient.

- **Monitoring is part of administration**  
  Administering Azure is not only about deployment. It includes active observability: metrics, logs, alerts, diagnostics, health checks, and operational baselines. A well-run Azure environment is one that can detect problems early and respond decisively.

- **Cost management is a design concern**  
  Azure offers flexibility and scale, but without deliberate resource planning, cost can grow quickly. Effective administrators view cost as an architecture topic, balancing performance, availability, security, and budget in every decision.

---

## About the Certification

The Microsoft Azure Administrator Associate certification (exam AZ-104) is designed for professionals who manage and monitor Azure environments, implement identity and governance, and support compute, networking, storage, and security services.

What the exam actually measures is judgment under realistic operational conditions. It is not simply testing memorization of service names or portal steps. It is testing whether a candidate can design and operate Azure workloads in a way that is secure, resilient, scalable, and aligned with organizational needs.

### Exam Overview

**Exam Code**: AZ-104  
**Certification**: Microsoft Certified: Azure Administrator Associate  
**Focus Area**: Day-to-day administration and operational management of Azure resources

The exam emphasizes practical administration skills, including:
- Managing Azure identities and access
- Implementing governance and policy
- Configuring networking and connectivity
- Deploying and maintaining compute resources
- Managing storage and data services
- Monitoring and troubleshooting Azure environments
- Ensuring security, compliance, and recovery readiness

---

## What You'll Learn

This study guide is structured around the major domains of the Azure Administrator (AZ-104) exam. Each module is designed to build both conceptual understanding and hands-on confidence in managing Azure services in real-world environments.

### Knowledge Areas Covered

- **Azure identity and access management**  
- **Role-based access control (RBAC)** and authorization models  
- **Microsoft Entra ID** and directory services  
- **Azure governance and Azure Policy**  
- **Resource groups, subscriptions, and management groups**  
- **Virtual networking and connectivity**  
- **Azure compute services** and VM management  
- **Azure storage solutions** and configuration  
- **Monitoring, diagnostics, and alerts**  
- **Backup, recovery, and operational resilience**  
- **Security best practices** and configuration review  
- **Troubleshooting and environment maintenance**

### Learning Resources in Each Module

- **Conceptual explanations** → Clear breakdowns of Azure administration principles  
- **Architecture diagrams** → Visual representations of Azure networking and service relationships  
- **Implementation walkthroughs** → Practical examples of common admin tasks  
- **Scenario-based questions** → Practice for real exam conditions  
- **Exam-focused notes** → Key takeaways aligned with certification objectives

---

👉 In short: this guide doesn’t just teach you what Azure features exist — it shows you how administrators make decisions, enforce control, and keep environments healthy in production.

## Repository Structure

This guide is organized into individual learning modules, allowing readers to move from fundamentals to advanced administration concepts in a structured, progressive way. Topics are grouped to reflect the real operational flow of Azure administration.

Throughout the guide you’ll find:

- Architecture diagrams → Visual breakdowns of networking, identity, and service design
- End-to-end explanations → Clear walkthroughs of cloud operations in practice
- Real-world examples → Case studies and applied scenarios for Azure environments
- Anti-patterns → Common administration mistakes and how to avoid them
- Decision frameworks → Tools for balancing cost, security, performance, and reliability
- Exam tips → Strategies for certification preparation and interview readiness
- Hands-on exercises → Practical examples using Azure Portal, CLI, PowerShell, and Azure-native services

---

## Intended Audience & Prerequisites

This study guide is designed for:

- Azure administrators
- Cloud engineers
- IT operations professionals
- Systems administrators transitioning to Azure
- DevOps engineers working with Azure infrastructure
- Candidates preparing for the Microsoft AZ-104 exam

### Recommended Prerequisites

**Basic cloud concepts**  
Familiarity with core cloud principles such as virtual machines, storage, networking, and identity.

**Azure fundamentals**  
A basic understanding of the Azure platform, resource hierarchy, and common services.

**Networking fundamentals**  
Knowledge of IP addressing, routing, DNS, subnets, and basic connectivity patterns.

**Security awareness**  
Understanding of identity, role-based access, authorization, and secure configuration practices.

**Operational mindset**  
Comfort with troubleshooting, monitoring, configuration review, and managing production systems.

---

## Disclaimer

This repository is an independent, community-maintained educational resource intended to assist learners preparing for the Microsoft Azure Administrator Associate certification exam, AZ-104. It is created for study and knowledge-building purposes and is not an official Microsoft publication.

This resource is not affiliated with, endorsed by, or sponsored by Microsoft. No warranties, express or implied, are made regarding the completeness, accuracy, or timeliness of the information provided.

Certification objectives, Azure platform features, and exam expectations may change over time. Learners are responsible for validating all information against the official Microsoft learning materials and current exam documentation.

By using this repository, you acknowledge that it is a supplementary study aid and not a substitute for official Microsoft preparation resources.
