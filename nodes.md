## The Nodes I Used

I want to be fully transparent about how I built this.

Here is every single node inside this workflow
and exactly what it does.

---

### Node 1 — Telegram Trigger (On Message)

This is the starting point.

It sits and listens to your Telegram bot 24/7.
The moment someone sends a message,
this node wakes up and passes the data forward.

Think of it as your front door bell.
Silent. Always on. Never misses a ring.

---

### Node 2 — Edit Fields

Telegram sends a lot of raw data.
Most of it you don't need.

This node acts like a filter.
It picks out exactly three things:

- Name — who sent the message
- Message — what they said
- Chat ID — their unique Telegram address

Clean. Simple. Organised.

---

### Node 3 — Google Sheets (Append Row)

This node takes the cleaned data
and writes it into your Google Sheet.

Every message = one new row.
Automatically. Instantly. Forever saved.

You never have to copy paste anything manually again.

---

### Node 4 — Telegram (Send Message)

After saving the lead,
this node sends an instant reply back to the user.

They get a confirmation message immediately.
They feel valued. They stay. They trust you.

---

### Full Node Flow

Telegram Trigger
      ↓
Edit Fields
      ↓
Google Sheets
      ↓
Telegram Reply
