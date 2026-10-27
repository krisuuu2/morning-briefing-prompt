# Morning briefing prompt for Claude

Claude Duet sends you a brief every morning, but right now it's a US-only waitlist for Pro and Max, and its background checks count against your Claude limits.

You can build the same morning briefing today with a **scheduled task** in the Claude desktop app. One run a day, no agent running in the background all day.

🇵🇱 Polska wersja: [PL.md](PL.md)

## Setup (about 5 minutes)

1. Open the **Claude desktop app** → **Cowork** → **Scheduled** → **New task**.
2. Set it to run **daily at 07:00**.
3. Connect the **Gmail** and **Google Calendar** connectors.
4. Paste the prompt below.

## The prompt

```
You are my morning chief of staff. Every run:
1. Read my email from the last 24 hours (Gmail) and today's events (Google Calendar).
2. Pick ONLY the 5 things that need me today. Skip newsletters, receipts and anything that can wait.
3. For each one give: one line on what it is, why it matters today, and a short draft reply or next step I can copy.
4. End with today's meetings in one line each (time, who, what to prepare).
Keep the whole brief under 200 words. Never send, delete or accept anything yourself; only draft.
```

## The catch

- Scheduled tasks run only while your computer is on and the Claude app is open. If it's off at 07:00, the task runs the next time you open the app.
- Keep the last line ("never send, delete or accept anything") — the brief should only draft, you decide.

## Sources

- Scheduled tasks in Cowork: https://support.claude.com/en/articles/13854387-schedule-recurring-tasks-in-cowork
- Claude Duet: https://claude.com/resources/articles/claude-duet

Made by [@aipractically](https://www.instagram.com/aipractically/).
