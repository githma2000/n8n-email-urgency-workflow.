# n8n-email-urgency-workflow.
n8n workflow for automatically detecting urgent emails using GPT-4. Includes Gmail triggers, AI classification, and automatic notifications. Sensitive credentials are removed; configure your own before running
# n8n Email Urgency Workflow

This repository contains an **n8n workflow** that automatically detects urgent emails using **GPT-4**.  

## Features
- Gmail trigger to detect incoming emails
- GPT-4 classification for urgency ("Urgent" / "Not Urgent")
- Automatic notification to your team or yourself
- Gmail label applied for processed emails

## Important Notes
- **Credentials are removed** from this file for security. Replace with your own:
  - Gmail credentials: `GMAIL_CREDENTIAL_ID`
  - OpenAI credentials: `OPENAI_CREDENTIAL_ID`
  - Notification emails: `YOUR_TEAM_EMAIL_HERE`
- Workflows need to be activated in n8n after import.

## Usage
1. Import the JSON workflow into your n8n instance.
2. Add your own credentials and activate the workflow.
3. Test with a few emails before full deployment.

## Disclaimer
- This workflow is provided as a template. Always protect your credentials.
- Using Gmail or OpenAI APIs may require sufficient quota or API access.

