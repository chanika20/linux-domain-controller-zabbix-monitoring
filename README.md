# Linux-based Domain Controller with Zabbix Monitoring

This project demonstrates the deployment of a Linux-based Active Directory domain controller integrated with Zabbix monitoring for infrastructure visibility.

## Features

- **Active Directory Integration:**
  - Samba 4 configured as a domain controller (`dc.gayashan.ch`)
  - Fedora client joined to the domain for centralized authentication

- **Monitoring:**
  - Zabbix 6.0 LTS server installed on Ubuntu 20.04
  - PostgreSQL 14 backend database
  - Zabbix agents installed on domain controller and client hosts
  - Custom templates and triggers for proactive monitoring

- **Technologies Used:**
  - Ubuntu Server 20.04
  - Samba 4
  - Zabbix 6.0 LTS
  - PostgreSQL 14
  - Fedora Workstation

## Setup Overview

1. Provision Ubuntu and Fedora machines
2. Configure Samba AD on Ubuntu
3. Join Fedora client to domain
4. Install and configure Zabbix server
5. Deploy Zabbix agents
6. Validate monitoring and alerting
