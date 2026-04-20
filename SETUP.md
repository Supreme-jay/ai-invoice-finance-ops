# Setup Guide

## 1. Import the Workflow
Import `workflow.json` into your n8n instance.

## 2. Groq Setup
Create a free Groq API key from console.groq.com.

Used for:
- invoice data structuring
- extraction support
- decision assistance where needed

## 3. Data Source / Trigger
Set up the trigger that starts the invoice workflow.

Possible triggers:
- webhook
- email attachment flow
- form submission
- invoice upload process
- spreadsheet or database event

## 4. Approval Routing
Configure approval rules based on your finance process.

Examples:
- amount threshold
- vendor type
- department
- invoice category
- approval level

## 5. Notifications
Connect your preferred notification tools in n8n.

Used for:
- approval requests
- invoice status updates
- escalation alerts
- final approval / rejection notices

## 6. Logging / Tracking
Connect the spreadsheet, Airtable, Google Sheets, database, or finance record store used to log:
- invoice details
- approval status
- approver
- timestamp
- action taken

## 7. Expected Flow
- invoice received
- key data extracted
- invoice routed for approval
- approver notified
- decision captured
- record updated
- finance ops log maintained

## 8. Notes
This project is portfolio-ready and may require reconnecting credentials after importing into another n8n environment.
