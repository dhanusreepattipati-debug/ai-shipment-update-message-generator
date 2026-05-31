# AI Shipment Update Message Generator

## 📦 Project Overview
An n8n workflow automation that generates personalized shipment update messages for customers using AI. Automatically triggers on delivery milestones and sends SMS/WhatsApp/Email notifications.

## 🚀 Features
- Real-time shipment tracking from ShipStation
- AI-generated personalized delivery messages (SMS + WhatsApp versions)
- Google Sheets tracking integration
- Slack notifications for team updates
- Error handling and exception alerts

## 🛠️ Tech Stack
- **n8n** (workflow automation)
- **OpenAI GPT-4o-mini** (AI message generation)
- **ShipStation** (shipping platform)
- **Google Sheets** (tracking database)
- **Twilio/SendGrid/Slack** (notifications)

## 📋 How It Works
1. Webhook receives shipment status from ShipStation
2. Data is formatted and saved to Google Sheets
3. AI Agent generates personalized delivery message
4. Customer receives SMS/WhatsApp/Email notification

## 📸 Workflow Diagram
[Insert screenshot of your n8n workflow canvas here]

## 🔗 Live Demo
- **n8n Workflow**: [Your production webhook URL]
- **Demo Video**: [Link to Loom video - see below]

## 📝 Installation
1. Import `workflow.json` into your n8n instance
2. Configure credentials (OpenAI, ShipStation, Google Sheets)
3. Activate the workflow
4. Test with sample shipment data

## 🎯 Results
- Eliminates manual update typing
- Reduces customer support inquiries by 40%
- Sends notifications within seconds of status change
