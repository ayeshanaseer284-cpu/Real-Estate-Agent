 Real-Estate-Agent
 Project Overview
This project is an automated payment reminder system designed for real estate businesses. It is built using n8n and helps agents or property managers automatically notify customers about unpaid or overdue payments.

The workflow reads customer payment data from Google Sheets, checks the payment status, and sends reminder emails accordingly. This reduces manual follow-ups and ensures timely communication with clients.

What This Project Does
The automation starts by fetching customer payment records from a Google Sheet. It then filters customers based on their payment status. If a payment is unpaid or overdue, the system automatically sends a personalized email reminder to the customer using Gmail.

This workflow helps real estate teams save time, reduce errors, and maintain professional communication.

Key Features
Automated payment reminders for customers
Reads real-time data from Google Sheets
Filters unpaid and overdue customers
Sends personalized email notifications
Fully automated workflow using n8n
No coding required

Workflow Explanation
Manual trigger starts the workflow
Google Sheets node fetches customer payment details
Filter node removes customers who have already paid
IF condition checks payment status
Unpaid customers receive a payment reminder email
Overdue customers receive an overdue payment warning email

Technology Used
n8n automation platform
Google Sheets API
Gmail API
Email-based notification system

Project Structure
Real estate agent (1).json
README.md

Setup Requirements
n8n installed locally or on cloud
Google account with access to Google Sheets
Gmail account connected to n8n
Basic understanding of n8n workflows

How to Use the Workflow
Open n8n
Import the workflow file Real estate agent (1).json
Connect your Google Sheets and Gmail credentials
Make sure your Google Sheet includes customer name, email, and payment status
Execute the workflow manually or schedule it as needed

Example Use Case
A real estate company wants to remind tenants about pending rent payments. Instead of checking records and sending emails manually, this automation sends reminders automatically based on payment status.

Future Improvements
Scheduled automatic execution
SMS or WhatsApp payment reminders
Payment gateway integration
Admin dashboard for payment tracking
Support for multiple properties

Author
Ayesha Naseer
AI Automation and Workflow Developer

License
This project is open-source and intended for educational and development use
This project is open-source and intended for educational and development use

