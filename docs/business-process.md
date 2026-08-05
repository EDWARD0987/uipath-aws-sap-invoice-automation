# Business Process - Invoice Automation

## Process Name

Accounts Payable Invoice Processing


## Current Manual Process

1. Vendor sends invoice through email
2. AP employee downloads invoice attachment
3. Employee reviews invoice information
4. Employee enters invoice data into SAP
5. Invoice document is stored
6. Confirmation email is sent


## Automated Process

1. UiPath monitors Outlook mailbox
2. Invoice attachment is downloaded
3. Invoice is stored in AWS S3
4. Amazon Textract extracts invoice information
5. Data validation rules are executed
6. UiPath creates invoice in SAP
7. Processing status is recorded
8. Notification email is sent


## Business Benefits

- Reduced manual processing
- Improved accuracy
- Faster invoice processing
- Better audit visibility
