# Server Inventory

## Infrastructure Servers

| Server Name | Description | Operating System | Network | Purpose |
|-------------|-------------|------------------|---------|---------|
| **dc01** | Primary Domain Controller | Windows Server | Infrastructure | Active Directory, DNS, DHCP services |
| **dc02** | Secondary Domain Controller | Windows Server | Infrastructure | AD replication, backup domain services |

## Database Servers

| Server Name | Description | Operating System | Network | Purpose |
|-------------|-------------|------------------|---------|---------|
| **db01-master** | Master Database Server | Windows Server | DB-Prod | Primary production database |
| **db02-slave** | Slave Database Server | Windows Server | DB-Prod | Database replication and backup |
| **db03-replica** | Reporting Database Replica | Windows Server | DB-Prod | Read-only replica for reporting |

## Application Servers

| Server Name | Description | Operating System | Network | Purpose |
|-------------|-------------|------------------|---------|---------|
| **app01-prod** | Production Stock Management | Windows Server | App-Prod | Primary stock management system |
| **app02-prod** | Production Stock Management | Windows Server | App-Prod | Load-balanced stock management |
| **app03-dev** | Development Stock Management | Windows Server | App-Dev | Development and testing environment |
| **iis01** | Primary Web Server | Windows Server | App-Prod | Web applications and services |
| **iis02** | Secondary Web Server | Windows Server | App-Prod | Load-balanced web services |

## Business Applications

| Server Name | Description | Operating System | Network | Purpose |
|-------------|-------------|------------------|---------|---------|
| **intra** | Intranet Portal | Linux | App-Prod | CRM, HR systems, employee portal |
| **DocFlow** | Document Management | Windows Server | App-Prod | Document flow, SharePoint services |
| **Reporting** | Business Intelligence | Windows Server | App-Prod | Power BI gateway and reporting |

## Special Services

| Server Name | Description | Operating System | Network | Purpose |
|-------------|-------------|------------------|---------|---------|
| **pbx** | VoIP Communication System | Linux | Voice | Internal telephony, call routing |
| **Jobs** | Scheduled Task Server | Linux | DevOps | Automated jobs, batch processing |

## Server Summary

- **Total Servers**: 16
- **Windows Servers**: 12
- **Linux Servers**: 4
- **Production Servers**: 11
- **Development Servers**: 1
- **Infrastructure Servers**: 4
