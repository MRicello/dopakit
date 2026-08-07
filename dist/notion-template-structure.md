# Dopakit - Notion Template Structure

## How to set this up in Notion

For each section below, create a new page in Notion or a database view. This document describes exactly what goes where. Follow it in order. Takes about 30 minutes.

---

## 1. The Dashboard (Main Page)

Create a new page called "Dashboard". Add these blocks:

### Top section
- **Header**: Today's date (use `/date` to make it dynamic)
- **Quote block**: "Progress, not perfection."
- **Divider**

### Three-column layout (use `/columns`)

**Column 1 - Today**
- Heading: "Today"
- To-do list block with these pre-filled items (user edits daily):
  - [ ] Task 1
  - [ ] Task 2
  - [ ] Task 3
  - [ ] Task 4
  - [ ] Task 5
- Toggle block: "Small wins"
  - Bullet list for completed micro-tasks

**Column 2 - This Week**
- Heading: "This Week"
- Bullet list:
  - Priority 1
  - Priority 2
  - Priority 3
- Toggle: "Next week"
  - Empty bullet list

**Column 3 - Energy & Focus**
- Heading: "Energy Level"
- Select property with options: High / Medium / Low
- Callout block (blue background): "Match your hardest task to your highest energy window today."
- Link to Energy Management page

### Bottom section
- **Divider**
- **Linked database**: "Client Projects" (filtered to Active)
- **Linked database**: "Content Queue" (showing next 3 items)

---

## 2. Task Breakdown Templates (Sub-page)

Create a sub-page under Dashboard called "Task Templates".

For each template, create a toggle block with the task name and a checklist inside:

### Template: Client Onboarding
- [ ] Send welcome email
- [ ] Create project folder
- [ ] Set up invoice draft
- [ ] Schedule kickoff call
- [ ] Share onboarding doc
- [ ] Add to client tracker

### Template: Weekly Admin
- [ ] Clear inbox to zero
- [ ] Send outstanding invoices
- [ ] Review this week's deadlines
- [ ] Update project statuses
- [ ] Check subscriptions/bills
- [ ] File receipts

### Template: Content Sprint
- [ ] Pick topic from idea list
- [ ] Write messy first draft (no editing)
- [ ] Let it sit for 2 hours
- [ ] Edit and format
- [ ] Create social versions
- [ ] Schedule or publish

### Template: Tax Prep
- [ ] Download bank statements
- [ ] Categorize last month's transactions
- [ ] Calculate income total
- [ ] Calculate expense total
- [ ] Update tax estimate spreadsheet
- [ ] Set aside tax amount in separate account

### Template: Project Kickoff
- [ ] Write scope doc
- [ ] Create timeline
- [ ] Identify dependencies
- [ ] Draft client comms
- [ ] Set up project in tracker
- [ ] Schedule first milestone check

---

## 3. Weekly Planner (Sub-page)

Create a sub-page under Dashboard called "Weekly Planner".

### Sunday Setup Ritual
- Callout block: "Sunday, 10 minutes. Grab coffee. Answer these:"
- Numbered list:
  1. What's the ONE thing that must happen this week?
  2. What meetings or deadlines are fixed?
  3. What can I say no to?
  4. What does a good week look like?

### Weekly Layout
- Table with columns: Day | Focus Block (9-11am) | Afternoon | Non-negotiable
- Pre-fill days Monday through Friday
- Include buffer rows between days

### Focus Sprint Tracker
- Bullet list: "Sprints completed this week:"
- Each sprint = 25 min work + 5 min break
- Goal: 4-8 sprints per day, not 16

---

## 4. Body Doubling (Page)

Create a page called "Body Doubling".

- Link to the Body Doubling Guide PDF
- Callout: "Schedule a session this week. Even one helps."
- Toggle: "My body doubling partners"
  - Name, contact, usual schedule
- Toggle: "Session log"
  - Table: Date | Duration | What I worked on | How it went
- Link to Focusmate (external)

---

## 5. Client Project Manager (Database)

Create a new database called "Client Projects".

### Properties
- Name (title)
- Client (select - add your clients)
- Status (select): Lead / Active / Waiting / Done
- Priority (select): High / Medium / Low
- Deadline (date)
- Next Step (text)
- Last Updated (date, auto)

### Views
- **Active Projects** (filter: Status = Active, sort by Deadline)
- **By Client** (group by Client)
- **Waiting** (filter: Status = Waiting)
- **Done** (filter: Status = Done)

### Template for new projects
- Status: Lead
- Next Step: "Send proposal"
- Callout: "What's the smallest next step? Do that first."

---

## 6. Dopamine Menu (Page)

Create a page called "Dopamine Menu".

### 5-minute rewards (pick one after completing 2 micro-tasks)
- Stand up and stretch
- Make tea or coffee
- Step outside for 60 seconds
- Pet the cat/dog
- One song you love (loud)
- Send a voice note to a friend
- 20 jumping jacks
- Wash your face with cold water

### 15-minute rewards (after completing a focus sprint)
- Watch one YouTube video
- Read one article you saved
- Play one round of a game
- Call someone for a quick chat
- Take a walk around the block

### 30-minute rewards (after finishing a project milestone)
- Watch an episode of a show
- Order your favorite lunch
- Take a nap
- Read a chapter of a book
- Go to a cafe and do nothing

### Rules
- Earn rewards. Don't pre-reward.
- No phone scrolling as a reward. It doesn't work.
- If you take a reward and can't get back to work, the reward was too big. Go smaller next time.

---

## 7. Money Tracker (Google Sheets link)

Embed or link to the Google Sheets tracker. See the separate Google Sheets file.

Key info to display on this page:
- Current month income (linked from Sheets)
- Tax set-aside amount
- Next invoice due dates

---

## 8. Energy Management (Page)

Create a page called "Energy Management".

### Chronotype quick assessment
- Callout: "When do you naturally feel most alert? Morning (6-11am), Midday (11am-3pm), or Evening (3pm-9pm)?"
- Text: "There's no wrong answer. Plan your hard tasks for YOUR peak, not someone else's."

### Energy-to-task matching
- Table:
  | Energy Level | Do This | Avoid This |
  | High | Deep work, writing, strategy, difficult conversations | Email, admin, meetings |
  | Medium | Meetings, planning, research, code review | Starting new complex projects |
  | Low | Email, admin, filing, data entry, simple fixes | Important decisions, client calls |

### Decision fatigue minimizer
- Toggle: "Decisions I've already made"
  - "What I eat for breakfast"
  - "What I wear on work days"
  - "Which project management tool I use"
  - (add your own to reduce daily decision load)

---

## 9. Content System (Database)

Create a database called "Content Queue".

### Properties
- Title (title)
- Type (select): Blog / Social / Email / Video
- Platform (select): Website / Twitter / LinkedIn / Instagram / Email
- Status (select): Idea / Draft / Scheduled / Published
- Publish Date (date)

### Views
- **Ideas** (filter: Status = Idea)
- **This Week** (filter: Publish Date is this week)
- **By Platform** (group by Platform)

### Idea Parking Lot
- At the top of the page: Callout block "Drop ideas here immediately. Don't try to remember them."
- Quick-capture: Just type the idea. Don't format. Don't judge. Refine later.

---

## 10. Reset Protocols (Page)

Create a page called "Reset".

### Bad Brain Day Protocol
- Callout: "Some days your brain just won't cooperate. That's fine. Here's the plan."
- Checklist:
  - [ ] Acknowledge it. Say out loud: "Today's a bad brain day."
  - [ ] Pick ONE thing. The smallest, easiest task on your list. Do only that.
  - [ ] If even that feels impossible: take a shower, eat something, go outside for 10 minutes.
  - [ ] After the break, try the one small thing again.
  - [ ] If it still doesn't happen: declare today a maintenance day. Answer emails. Organize files. Do the low-energy stuff.
  - [ ] No guilt. Bad brain days happen. Tomorrow is another shot.

### Overwhelm Procedure
- Numbered list:
  1. Stop. Close all tabs you're not actively using.
  2. Write down everything that's swirling in your head. Every task, worry, obligation.
  3. Circle the three things that actually matter this week.
  4. Cross out everything that can wait until next week or doesn't matter at all.
  5. Pick the smallest next step from the circled items.
  6. Do that one thing.
  7. Repeat.

### Monthly Review
- Template questions (answer in a toggle block):
  - What got done this month? (List everything - you did more than you think)
  - What kept getting pushed to next week? (Pattern detection)
  - What part of the Dopakit system did I actually use?
  - What part did I ignore?
  - What's ONE thing I'll change next month?

---

## Setup Complete

That's the full workspace. Once built, it's yours to customize. Add your clients. Fill in your energy peak. Set up your first body doubling session. The system is the skeleton - you add the muscle.
