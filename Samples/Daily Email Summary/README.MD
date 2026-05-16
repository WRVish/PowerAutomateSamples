# Daily AI Email Summary

This Power Automate solution generates a daily AI-powered summary of unread Outlook emails, helping users quickly identify messages that may require attention without manually reviewing the entire inbox.

---

# Overview

The flow runs on a daily schedule and analyses unread emails received within the last 7 days.

Using AI Builder, it generates a concise summary highlighting emails that may require follow-up, responses, or action. The final output is delivered as a formatted email containing direct links to open each message in Outlook.

---

# High-Level Flow

```text
Recurrence Trigger
    ↓
Get Emails (V3)
    ↓
Filter Recent Emails
    ↓
Prepare Email Data
    ↓
AI Builder – Run a Prompt
    ↓
Send AI Summary Email
```

---

# Features

- Daily automated inbox review
- AI-generated email prioritisation
- Summary focused on actionable emails
- Click-to-open Outlook email links
- Reduces missed follow-ups
- Lightweight and easy to extend

---

# Technologies Used

- Microsoft Power Automate
- Office 365 Outlook Connector
- AI Builder
- Microsoft 365

---

# Use Cases

- Daily inbox summaries
- Follow-up tracking
- Action item detection
- Executive email review
- Productivity automation

---

# Blog

For the full implementation walkthrough, setup instructions, AI prompt design, and troubleshooting details, read the blog post:

## Daily AI Email Summary with Power Automate

https://www.wrvishnu.com/daily-ai-email-summary-power-automate/

---

# Discussion & Ideas

Some possible enhancements and discussion points:

- Should the AI classify emails by urgency automatically?
- Would Teams notifications work better than email summaries?
- Could this be extended to generate draft replies?
- Should reminders persist until an email is resolved?
- Would sentiment analysis improve prioritisation?
- Could the same pattern be used for support tickets or approvals?

Feel free to raise ideas, improvements, or alternative approaches through discussions and issues.

---

# License

MIT License
