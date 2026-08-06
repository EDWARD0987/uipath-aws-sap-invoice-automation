# UiPath AWS SAP Invoice Automation
Enterprise Intelligent Automation solution integrating UiPath RPA, AWS cloud services, and SAP ERP to automate invoice processing workflows.

## Overview

Enterprise Intelligent Automation solution integrating UiPath RPA, AWS cloud services, and SAP ERP to automate Accounts Payable invoice processing.

The solution automates the end-to-end invoice lifecycle:

- Email ingestion
- Document extraction
- Data validation
- SAP invoice creation
- Cloud storage
- Logging and monitoring

---

# Business Problem

Accounts Payable teams manually process large volumes of vendor invoices.

Current process:

1. Receive invoice email
2. Download invoice attachment
3. Extract invoice information
4. Enter invoice details into SAP
5. Store documents
6. Notify stakeholders

Challenges:

- Manual effort
- Data entry errors
- Slow processing
- Limited visibility

---

# Solution

The automation workflow:

Vendor

↓

Microsoft Outlook

↓

UiPath Robot

↓

AWS S3

↓

Amazon Textract

↓

Validation

↓

SAP ERP

↓

SQL Database

↓

CloudWatch Monitoring

---

# Technology Stack

## Robotic Process Automation

- UiPath Studio
- UiPath Orchestrator
- REFramework

## AWS Services

- Amazon S3
- Amazon Textract
- AWS Secrets Manager
- Amazon CloudWatch
- AWS Lambda

## Enterprise Systems

- SAP ERP
- Microsoft Outlook
- SQL Server

---

# Project Status

## Phase 1 - Documentation and Architecture

Status: In Progress

## Phase 2 - UiPath Development

Status: Planned

## Phase 3 - AWS Integration

Status: Planned

## Phase 4 - SAP Automation

Status: Planned

## Phase 5 - Production Hardening

Status: Planned


# Solution Architecture

![Architecture Diagram](diagrams/architecture.png)
