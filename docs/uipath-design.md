# UiPath Automation Design

## Process Name

Invoice Processing Automation


## Workflow

1. Read invoice email from Outlook
2. Download attachment
3. Store document in AWS S3
4. Extract invoice data
5. Validate invoice information
6. Create invoice in SAP
7. Update processing status
8. Send notification


## Framework

REFramework


## Transaction Item

Invoice


## Business Exceptions

- Missing vendor
- Missing invoice number
- Invalid amount


## System Exceptions

- Outlook unavailable
- SAP connection failure
- AWS API failure
