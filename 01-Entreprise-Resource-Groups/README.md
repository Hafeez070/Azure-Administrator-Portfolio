# Enterprise Azure Resource Group Governance Foundation

| Property | Value |
|----------|-------|
| Project Number | 01 |
| Module | Governance |
| Difficulty | Beginner |
| Estimated Completion Time | 30 Minutes |
| Azure Services Used | 4 |
| Deployment Method | Azure Portal |
| Status | ✅ Completed | 

## Business Scenario

PrimeLink Solutions Ltd. is a growing technology company that is migrating its on-premises infrastructure to Microsoft Azure.

As part of the cloud adoption initiative, the Azure Administrator has been assigned to establish a governance foundation that ensures Azure resources are consistently organized, protected against accidental deletion, and prepared for future expansion.

The organization requires a standardized naming convention, resource tagging strategy, and governance controls that will support future deployments of virtual machines, storage accounts, networking resources, and monitoring services.

## Business Requirements

The organization requires the Azure environment to:

- Organize cloud resources using a standardized Resource Group structure.
- Apply a consistent naming convention across Azure resources.
- Implement resource tags to improve cost management and governance.
- Protect production resources from accidental deletion.
- Establish a scalable governance foundation for future Azure deployments.

## Azure Services and Features Used

- Azure Resource Groups
- Azure Resource Manager (ARM)
- Azure Resource Tags
- Azure Resource Locks

## Tools Used

- Microsoft Azure Portal
- Git
- GitHub
- Markdown

## Architecture Diagram

                 Azure Subscription
                        │
                        │
          ┌─────────────────────────┐
          │ Resource Group          │
          │ rg-primelink-prod-uks-01│
          └─────────────────────────┘
                     │
         ┌───────────┴───────────┐
         │                       │
      Resource Tags         Delete Lock

## Architecture Overview

This project establishes the governance foundation for PrimeLink Solutions Ltd.'s Azure environment by implementing a dedicated Resource Group with a standardized naming convention, governance tags, and a Delete Lock. These configurations provide a structured management boundary that supports secure, scalable, and well-organized Azure resource deployments.

