# ai-email-approval-workflow-n8n
AI-powered Gmail reply approval workflow built with n8n, OpenAI, Slack, Google Sheets and Gmail.
# AI Email Approval Workflow using n8n

This project is an AI-powered email automation workflow built with n8n.

The workflow listens for new Gmail emails, uses an AI Agent to understand the message, checks business context from Google Sheets, sends the proposed reply to Slack for approval, and only sends the Gmail response once approved.

## Workflow Overview

1. A new email is received in Gmail
2. The AI Agent reads and understands the email
3. OpenAI generates a professional draft reply
4. Google Sheets provides business or customer context
5. Slack sends an approval message
6. If approved, the reply is sent through Gmail

## Workflow Screenshot

![Workflow Screenshot](assets/workflow-screenshot.png)

## Tools Used

- n8n
- Gmail Trigger
- OpenAI Chat Model
- AI Agent
- Google Sheets
- Slack
- IF Condition
- Gmail Send Message

## Why I Built This

I built this workflow to demonstrate how AI can support real business communication while keeping human control in the process.

Instead of automatically sending AI-generated replies, the workflow sends the response to Slack for approval first. This makes the automation safer and more suitable for real business use.

## Use Cases

- Customer support email drafts
- Sales inquiry replies
- Lead follow-up emails
- Admin email automation
- Human-in-the-loop AI workflows

## Security Note

This repository does not include any real API keys, Gmail credentials, Slack tokens, OpenAI keys, or private email data.

All credentials must be configured inside n8n before running the workflow.
