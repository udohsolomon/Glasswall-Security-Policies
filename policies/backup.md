﻿
# Backup 

|                  |            | 
|------------------|------------|
| **ID**           | [Policy-5](https://glasswall.atlassian.net/browse/POLICY-5) |
| **Status**       |Approved by InfoSec, Awaiting Final Approval        |
| **Release Date** | TBD        |
| **Version**      | v2.1       |
| **Owners**       | [CISO](https://glasswall.atlassian.net/browse/ROLE-38), [CEO](https://glasswall.atlassian.net/browse/ROLE-37)       |
| **Stakeholders** | [Head of IT](https://glasswall.atlassian.net/browse/ROLE-43)|
			
 
## Contents

- 1.0 Overview
- 2.0 Purpose
- 3.0 Scope
- 4.0 Policy
- 4.1 Identification of Critical Data
  - 4.4.1 On Premise Physical backup
  - 4.4.2 Cloud backup
- 4.2 Data to be Backed Up
- 4.3 Backup Frequency
- 4.4 Backup Location
- 4.5 Backup Retention
- 4.7 Restoration Procedures & Documentation
- 4.8 Restoration Testing
- 4.9 Applicability of Other Policies
- 5.0 Enforcement
- 6.0 Definitions


 
## 1.0 Overview

This policy defines the backup policy for computer systems within the organisation that are expected to have their data backed up.

## 2.0 Purpose

The purpose of this policy is to protect company data to ensure it is not lost and can be recovered in the event of cyber-attack, equipment failure, natural disasters or human error.

## 3.0 Scope

This policy applies to all data stored on corporate systems.  The policy covers such specifics as the type of data to be backed up, frequency of backups, storage of backups, retention of backups, and restoration procedures.
 
Glasswall is hereinafter referred to as "the company."

## 4.0 Policy

## 4.1 Identification of Critical Data

The company must identify what data is most critical so that it can be given the highest priority during the backup process.

## 4.2 Data to be Backed Up

Data to be backed up includes the following:

- All data determined to be critical to company operations and/or employee job functions.  
- Systems to be backed up include but are not limited to:
- File servers
  - Mail servers
  - Production Infrastructure 
  - Production data
  - Production code
  - Non-Production Infrastructure 
  - Non-Production data
  - Non-Production code
  - Domain controllers
  - Standard builds for laptops and endpoints 
- Configuration of network devices such as, switches, routers, wireless access points etc.
- Logs for critical systems  .

## 4.3 Backup Frequency

Backups must be performed daily.

## 4.4 Backup Location

In order to protect from cyber-attack, equipment failure, natural disasters or human error, backup storage must use a third-party in addition to any onsite backup location.

### 4.4.1 On Premise Physical backup

In order to protect from loss of access to the third-party backup, a duplicate of the weekly backup should be stored onsite in a secure area.

To secure the backups, all backup media should be encrypted.

The onsite weekly backup must provide the ability to restore all On-Premise systems in the event of loss of access to the third party backup.

### 4.4.2 Cloud backup

Cloud backup is done on Real-Time using Automatic Geo Redundant backup.

 
## 4.5 Backup Retention

Backups must be retained as follows:

- Daily:   2 Weeks
- Weekly:  2 Months
- Monthly: 12 Months
- Annual:  7 Years
 
## 4.7 Restoration Procedures & Documentation

The data restoration procedures must be documented.

Documentation should include exactly who is responsible for the restore, how it is performed, under what circumstances it is to be performed, and how long it should take from request to restoration.

## 4.8 Restoration Testing

The ability to restore data from backups shall be tested at least once per month.

Backup restores must be tested when any changes are made that may affect the backup system.

## 4.9 Applicability of Other Policies

This document is part of the company's cohesive set of security policies.  Other policies may apply to the topics covered in this document and as such the applicable policies should be reviewed as needed.

## 5.0 Enforcement

This policy will be enforced by the Head of IT and/or Executive Team. Violations may result in disciplinary action, which may include suspension, restriction of access, or more severe penalties up to and including termination of employment. Where illegal activities or theft of company property (physical or intellectual) are suspected, the company may report such activities to the applicable authorities.

## 6.0 Definitions

Refer to Information Security Policy Guide.


