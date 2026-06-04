# 🤖 Telegram Lead Capture — n8n Automation

## What This Does

I built this workflow because I saw a real problem.

Every day, small business owners get messages 
on their Telegram bot — and miss them.

No reply. No record. Lost forever.

So I automated the whole thing.

Now when someone messages your Telegram bot,
two things happen instantly — without you touching anything:

- Their name, message and contact gets saved 
  to your Google Sheet automatically
- They get a friendly reply on Telegram immediately

You sleep. The bot works.
You are busy. The bot works.
You are on vacation. The bot works.

Zero missed leads. Zero manual work. Ever.

---

## The Problem I Solved

Let me be honest with you.

I talked to a lot of small business owners.
Coaches. Consultants. Shop owners.

And almost all of them had the same story.

"Someone messaged me on Telegram last week.
I forgot to reply. They never came back."

That one missed message could have been a paying customer.
That one missed lead could have been $500. $1000. More.

And the worst part?
They did not even know how many leads they were losing.
Because nothing was being saved anywhere.

No spreadsheet. No CRM. No record.
Just gone.

I built this workflow to fix exactly that.

---

## How It Works

I kept this simple on purpose.
No complicated setup. No coding. No technical headaches.

Step 1 — Someone messages your Telegram bot
They could say anything.
"I need help." "What are your prices?" "Are you available?"
Doesn't matter. The bot catches everything.

Step 2 — The workflow wakes up instantly
No delay. No waiting.
The moment the message arrives, n8n starts working.

Step 3 — Their details get cleaned and organised
Name. Message. Chat ID. Date.
All extracted. All neat. All ready to save.

Step 4 — Everything gets saved to your Google Sheet
One new row. Automatically.
You open your sheet in the morning and see every lead from the night before.

Step 5 — They get an instant reply on Telegram
They feel heard. They do not leave. They wait for you.

The whole process takes less than 3 seconds.
Fully automatic. Every single time.

---

## Workflow Screenshot

![Telegram Lead Capture Workflow](screenshots/workflow-screenshot.png)

---

## Flow Diagram

```
Telegram Message
        ↓
Workflow Starts
        ↓
Extract Name + Message + Chat ID
        ↓
Save to Google Sheets
        ↓
Send Reply to User
        ↓
Done ✅
```

---

## The Nodes I Used

### Node 1 — Telegram Trigger (On Message)
Listens to your Telegram bot 24/7.
The moment someone sends a message,
this node wakes up and passes the data forward.
Think of it as your front door bell.
Silent. Always on. Never misses a ring.

### Node 2 — Edit Fields
Picks out exactly three things:
- Name — who sent the message
- Message — what they said
- Chat ID — their unique Telegram address

Clean. Simple. Organised.

### Node 3 — Google Sheets (Append Row)
Takes the cleaned data and writes it into your Google Sheet.
Every message = one new row. Automatically. Instantly. Forever saved.
You never have to copy paste anything manually again.

### Node 4 — Telegram (Send Message)
Sends an instant reply back to the user.
They feel valued. They stay. They trust you.

---

## Google Sheet Structure

| name | user_message | chat_id | date |
|------|-------------|---------|------|
| Sarah | I need your service | 123456789 | 2026-06-04 |
| Ahmed | What is your price? | 987654321 | 2026-06-04 |
| John | Are you available? | 456789123 | 2026-06-04 |

---

## Who Needs This

- Small business owners losing leads daily
- Coaches and consultants missing client inquiries
- E-commerce store owners needing instant replies
- Freelancers and agencies too busy to watch Telegram
- Anyone using Telegram for customer support

---

## Real Questions From Real Buyers

**Will I miss any leads if my internet is down?**
No. n8n runs on the cloud. Works 24/7 regardless.

**What if someone sends 100 messages at once?**
Every single one gets saved. No duplicates. No missing entries.

**Can I change the reply message?**
Yes. One click. 30 seconds.

**Do I need coding knowledge?**
Zero. If you can use WhatsApp, you can use this.

**Where are my leads saved?**
In your own Google Sheet. Your data. Your control.

**Can my team see the leads too?**
Yes. Just share the Google Sheet. Everyone sees new leads in real time.

**How long does setup take?**
Under 15 minutes.

**Is this a one time setup?**
Yes. Set it up once. It runs forever.

---

## Download & Import Workflow

You can import this workflow directly into your n8n.

1. Download the file here:
[telegram-lead-capture.json](files/telegram-lead-capture.json)

2. Open n8n
3. Click Import Workflow
4. Upload the JSON file
5. Add your credentials
6. Publish and you are live

---

## What I Built This With

- n8n — workflow automation (free at n8n.io)
- Telegram Bot API — completely free
- Google Sheets API — completely free

This entire workflow runs without spending a single dollar.

---

## 💰 Hire Me — Pricing

I do not just send you a JSON file.
I set everything up for you.
Your bot. Your Google Sheet. Your business.
Tested. Live. Working.

| Package | Price | What You Get |
|---------|-------|-------------|
| **Basic** | $30 | Full workflow setup + your Google Sheet connected + tested + live |
| **Standard** | $50 | Everything in Basic + custom reply with your business name + 3 days support |
| **Premium** | $80 | Everything in Standard + 2 extra changes + 7 days support + video walkthrough |

---

## Why Work With Me

I show my full work right here on GitHub.
Every node. Every step. Every decision.
You can see exactly how I build before you spend a single dollar.

No surprises. No hidden steps. No confusion.
Just clean working automation delivered professionally.

---

## Ready To Get Started?

Message me on Fiverr or Upwork.
Tell me about your business.
I will tell you exactly how I can help.

Response time: under 2 hours.

I look forward to working with you.
