SSH Key Management System

Team 9 – Venkatbharat Poleneni & Jahnavi Kandoji Rao

Project Overview

The SSH Key Management System is a centralized solution designed to manage SSH keys securely throughout their lifecycle. The system enforces Zero Trust principles by ensuring that SSH access is granted only to authorized users for a defined duration using traceable and policy-compliant keys.
This project is developed as part of an Agile product planning assignment and is structured across 5 biweekly sprints over a 10-week timeline.

Vision

To eliminate unmanaged SSH keys in enterprise environments by providing automated discovery, lifecycle control, and enforcement mechanisms.

Key Objectives

Discover and inventory existing SSH keys
Centralize SSH key metadata storage
Enforce controlled key generation
Automate key rotation and revocation
Improve audit visibility and compliance readiness

System Architecture (High-Level)

The system consists of the following core components:
SSH Scanner Module – Detects and extracts SSH key metadata
Backend API – Handles business logic and system coordination
Database – Stores centralized SSH key records
Audit Logging Module – Tracks system activity

Technologies Used

Programming Languages
Python
SQL
Bash

Tools & Platforms

Jira (Scrum project management)
GitHub (version control)
Linux / UNIX systems
OpenSSH
PostgreSQL / SQLite
