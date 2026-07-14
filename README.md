# Ɔboafoɔ - AI Voice Sales Center

## Overview

Ɔboafoɔ is an AI-powered voice sales assistant designed to help businesses handle customer inquiries, qualify leads, automate CRM updates, and schedule sales meetings.

The system combines conversational AI with workflow automation to create an end-to-end sales support solution that operates 24/7.

---

## Problem

Businesses often lose potential customers because:
- Calls are missed outside working hours
- Sales teams spend too much time manually qualifying leads
- Customer information is scattered across different platforms
- Follow-ups are delayed

---

## Solution

Ɔboafoɔ acts as a virtual sales representative that:

- Answers customer conversations through voice
- Collects customer information
- Qualifies leads based on business requirements
- Stores lead information automatically
- Alerts sales teams instantly
- Creates follow-up meetings

---

## Workflow Architecture

The system follows an automated lead management workflow:
Customer Call
↓
ElevenLabs AI Voice Agent (Ɔboafoɔ)
↓
Lead Qualification & Data Extraction
↓
n8n Automation Workflow
↓
Google Sheets CRM
↓
Telegram Sales Notification
↓
Google Calendar Meeting Booking


---

## Key Features

✅ AI-powered voice conversations  
✅ Automated lead qualification  
✅ Customer information extraction  
✅ CRM data storage  
✅ Real-time sales notifications  
✅ Automated appointment scheduling  
✅ End-to-end workflow automation  

---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| ElevenLabs Agents | AI voice assistant and conversational interface |
| n8n | Workflow automation and system orchestration |
| Google Sheets | Lead management and lightweight CRM |
| Telegram Bot API | Sales team notifications |
| Google Calendar API | Automated meeting scheduling |
| Webhooks | Data transfer between systems |

---

## How It Works

### 1. Customer Interaction
A customer communicates with Ɔboafoɔ through a voice conversation.

### 2. Lead Qualification
The AI assistant asks relevant questions to understand:
- Customer needs
- Company information
- Budget
- Timeline
- Service interest

### 3. Data Processing
Collected information is sent through a webhook to n8n for processing.

### 4. CRM Update
Lead details are automatically stored in Google Sheets.

### 5. Sales Notification
The sales team receives an instant Telegram notification with the new lead details.

### 6. Meeting Scheduling
Qualified leads are automatically scheduled for a follow-up meeting through Google Calendar.

---
## Screenshots

### AI Voice Agent

Ɔboafoɔ uses ElevenLabs Agents to conduct natural voice conversations with customers and collect relevant sales information.

(Add ElevenLabs screenshot here)

---

### n8n Automation Workflow

The automation workflow connects the voice assistant to CRM, notifications, and scheduling systems.

(Add n8n workflow screenshot here)

---

### Lead CRM

Customer information collected during conversations is automatically stored in Google Sheets.

(Add Google Sheets screenshot here)

---

### Sales Notification

The sales team receives instant notifications when a new qualified lead is captured.

(Add Telegram screenshot here)

---

### Meeting Scheduling

Qualified prospects are automatically added to the sales calendar.

(Add Google Calendar screenshot here)

---

## Results

Built an end-to-end AI voice sales workflow that automates the customer acquisition process.

The system can:

- Handle customer conversations automatically
- Qualify potential leads
- Capture and organize customer information
- Reduce manual sales follow-up
- Notify sales teams instantly
- Schedule meetings automatically

---

## Future Improvements

Potential enhancements include:

- Connecting to a full CRM platform such as HubSpot or Salesforce
- Adding multilingual voice support
- Implementing advanced lead scoring
- Adding analytics dashboards for sales performance
- Integrating SMS and email follow-up campaigns

---

## Author

Built by Patricia Fleku

AI Automation | n8n | Voice AI | Business Process Automation
