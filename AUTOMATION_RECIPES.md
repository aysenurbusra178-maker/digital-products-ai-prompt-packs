# Automation Recipes (Make.com / n8n / Zapier)

Simple, practical automation ideas that pair with the Notion templates.
These are recipes you can implement yourself or offer as upsell documentation.

---

## 1. Sales Pipeline – Auto Follow-up Reminder

**Goal:** Never miss a follow-up.

**Tools:** Notion + Make.com / n8n + Email or Slack

**Flow:**
1. Watch Notion “Follow-up Tasks” database
2. Filter: Status = To Do AND Due Date = Today (or overdue)
3. Send email / Slack notification to yourself with deal name + next action
4. Optional: create a calendar event

**Value:** Turns the Sales Pipeline template into a real automatic follow-up system.

---

## 2. Freelance Invoice – Payment Reminder

**Goal:** Automatic gentle reminders for unpaid invoices.

**Flow:**
1. Watch Invoices database
2. Filter: Status = Sent AND Due Date passed
3. Send templated email to client (or to yourself as reminder)
4. After 3 reminders → change status to Overdue

---

## 3. Content Calendar – Publishing Reminder

**Goal:** Never forget to publish.

**Flow:**
1. Watch Content Calendar
2. Filter: Status = Scheduled AND Publish Date = Today
3. Send morning Slack / email with the post caption + platform
4. Optional: push the caption to a Google Doc or Buffer draft

---

## 4. New Lead → Pipeline + Task

**Goal:** Every new lead automatically creates a follow-up task.

**Flow:**
1. New page created in Sales Pipeline (Stage = Lead)
2. Create related Follow-up Task: “First contact call” due in 24h
3. Notify yourself

---

## How to Use These Recipes

- Implement them yourself for your own business
- Or package the recipes as a free / paid bonus when selling the Notion templates
- Tools: Make.com (easiest), n8n (self-hosted), or Zapier

These recipes complete the “automation hybrid” promise of the original idea.
