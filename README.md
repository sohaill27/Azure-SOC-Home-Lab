# Azure SOC Home Lab | Security Monitoring & Log Analysis

## Project Overview

This project demonstrates the implementation of a cloud-based Security Operations Center (SOC) home lab using Microsoft Azure. The lab focuses on collecting, monitoring and analysing Windows Security Event Logs using Azure Log Analytics and Kusto Query Language (KQL).

The objective was to gain practical experience with cloud-based security monitoring, Windows event logging and fundamental SOC operations.

## Technologies & Tools

- Microsoft Azure
- Azure Virtual Machines
- Windows Operating System
- Azure Log Analytics
- Kusto Query Language (KQL)
- Windows Security Event Logs
- Network Security Groups (NSG)
- Remote Desktop Protocol (RDP)

## Lab Architecture

The lab consists of a Windows virtual machine hosted in Microsoft Azure, connected to an Azure Log Analytics workspace for security event collection and analysis.

**Workflow:**

Windows Virtual Machine (CORPNET)  
↓  
Windows Security Event Logs  
↓  
Azure Log Analytics Workspace  
↓  
KQL Queries  
↓  
Security Event Monitoring & Analysis

## Implementation Steps

### 1. Azure Virtual Machine Setup
- Created a Windows virtual machine named CORPNET.
- Configured the virtual machine and network settings.
- Established remote access using Remote Desktop Protocol (RDP).

### 2. Network Configuration
- Configured Azure Network Security Group (NSG) rules.
- Configured inbound access for Remote Desktop.
- Tested network connectivity.

### 3. Log Analytics Workspace
- Created an Azure Log Analytics workspace.
- Configured the workspace for Windows security event monitoring.
- Verified that security event records were being received.

### 4. Security Event Collection
- Collected Windows Security Event Logs from the virtual machine.
- Verified the availability of security records in Log Analytics.

### 5. KQL-Based Log Analysis
Used Kusto Query Language to retrieve and inspect security events.

**Query:**

```kql
SecurityEvent
```

This query retrieves Windows security event records from the Log Analytics workspace.

## Key Learnings

- Understanding SOC monitoring fundamentals.
- Working with Microsoft Azure cloud infrastructure.
- Configuring and managing Windows virtual machines.
- Understanding Windows Security Event Logs.
- Collecting and analysing security logs.
- Writing basic KQL queries.
- Understanding network security rules and remote access.

## Project Screenshots

Screenshots demonstrating the implementation and results will be added here.

## Future Improvements

- Integrate Microsoft Sentinel for SIEM capabilities.
- Develop KQL queries for failed login detection.
- Investigate suspicious authentication activity.
- Create security monitoring dashboards.
- Develop incident detection and investigation workflows.

## Disclaimer

This project was developed in a controlled educational environment for cybersecurity learning and practical skill development.
