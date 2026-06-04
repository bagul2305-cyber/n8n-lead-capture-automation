# N8N Lead Capture Automation

## What This Project Does
An automated lead capture system built with n8n that:
- Receives form submissions via webhook
- Writes lead data to Google Sheets automatically
- Sends an email confirmation to the person who submitted

## Tech Stack
- n8n (workflow automation)
- Google Sheets API
- Gmail API
- HTML/JavaScript (frontend form)

## How It Works
1. User fills out the HTML contact form
2. Form sends a POST request to an n8n webhook
3. n8n writes the data to Google Sheets
4. n8n sends a confirmation email via Gmail

## Skills Demonstrated
- Webhook configuration
- REST API integration
- OAuth2 authentication
- Data mapping between systems
- End-to-end automation logic
