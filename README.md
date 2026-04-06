# Medication Reminder

A simple, free medication reminder app for families managing a loved one's care.

No app store. No account. No installation. Just bookmark a URL.

**[→ Open the app](https://maurakrandall.github.io/medication-reminder/medication-reminder.html)**

---

## Why this exists

I built this during a caregiving break — the period when I stepped back from full-time product leadership to help care for my parents.

Managing two people's medications across multiple times of day is genuinely hard to track. The apps that exist are either overcomplicated, expensive, or require accounts and cloud sync that elderly parents can't navigate. I needed something a non-technical caregiver could set up in five minutes and a senior could use without asking for help.

So I built it. One conversation with my AI teammate Soph (Claude). One afternoon. One HTML file.

It works.

---

## What it does

**For the caregiver (setup + management)**
- Add medications with name, dosage, plain-language purpose, and who they belong to
- Set which days and which times of day (morning / noon / evening / bedtime)
- Edit or archive medications at any time — nothing is permanently deleted
- Manage medications for two people from one place

**For the person taking medications (daily view)**
- See today's medications grouped by time of day
- Large text, high contrast, simple checkboxes
- Check off each medication as it's taken
- Progress bar showing how many are done

Everything resets fresh each day. Data stays on the device — nothing is sent anywhere.

---

## How to use it

1. Open the app link above and bookmark it on your phone
2. Tap **+ Add** to enter the first medication
3. Share the same link with whoever needs to see the daily view
4. They bookmark it too

That's the entire setup.

---

## Technical details

For anyone who wants to fork, customize, or self-host:

- Single HTML file — no dependencies, no build step
- Vanilla JavaScript — no frameworks
- Data stored in `localStorage` — stays on the device, never transmitted
- Works offline after first load
- Designed mobile-first for phones and tablets
- Large touch targets throughout — built for fingers, not mice

To deploy your own copy: download `medication-reminder.html`, push it to any static host (GitHub Pages, Netlify, etc.), and share the URL.

---

## Built with the Human-AI Loop

This app is an example of what I call the Human-AI Loop in practice — using AI not as a vending machine, but as a genuine collaborator on real work.

**The prompt that started this:** a one-page brief I wrote in about 20 minutes, describing the problem, the users, and what simple actually means for elderly parents.

**What Soph (Claude) did:** translated the brief into a working, production-ready app in a single pass.

**What I did:** held the intent. Knew what my parents actually needed. Made the judgment calls about what to leave out. Decided when it was done.

The Loop doesn't end when something is produced. It ends when a human decides what to do with it.

More on the methodology: [thehumanailoop.com](https://thehumanailoop.com)

---

## Free to use and fork

Take it. Customize the names, colors, or time-of-day labels. Add a time zone. Build in Google Calendar export. Whatever you need.

If you use it and it helps your family, that's enough.

---

*Built by [Maura Randall](https://maurakrandall.com) and Soph (Claude) · April 2026*
