## Setup Guide

I want to be completely honest with you.

Setting this up is easier than you think.
I have broken it down into simple steps
so anyone can follow along.

No technical background needed.
No coding knowledge required.
Just follow the steps.

---

### What You Need Before Starting

1. A Telegram account
2. A Google account
3. An n8n account (free at n8n.io)
4. 15 minutes of your time

That is it.
Nothing else.

---

### Step 1 — Create Your Telegram Bot

Open Telegram.
Search for BotFather.
Type /newbot
Give your bot a name.
Give your bot a username.
Copy the token BotFather gives you.

Keep that token safe.
It is the key to your bot.

---

### Step 2 — Set Up n8n

Go to n8n.io
Create a free account.
Open a new workflow.
Add the Telegram Trigger node.
Paste your bot token into the credential.
Select On Message as the trigger.

---

### Step 3 — Create Your Google Sheet

Open Google Sheets.
Create a new spreadsheet.
Add these column headers in Row 1:

- A1: name
- B1: user_message
- C1: chat_id
- D1: date

---

### Step 4 — Connect Google Sheets to n8n

Add a Google Sheets node in n8n.
Connect your Google account.
Select your spreadsheet.
Select Append Row as the operation.
Map the fields:

- name → name from Telegram
- user_message → message from Telegram
- chat_id → chat ID from Telegram
- date → current date and time

---

### Step 5 — Add Telegram Reply

Add a Telegram node.
Select Send Message.
Set Chat ID to dynamic expression.
Write your reply message.

---

### Step 6 — Test Everything

Click Test Workflow.
Send a message to your bot on Telegram.
Check that all nodes turn green.
Check that your Google Sheet has a new row.
Check that you received a reply on Telegram.

---

### Step 7 — Publish

Click Publish.
Your workflow is now live.
It will run automatically forever.

---

### Need Help With Setup?

I offer full setup support.
Just message me and I will help you
get this running in under 15 minutes.

No extra charge for my buyers.
