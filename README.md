# Thinker's Log

A 52-week reading plan for first-principles thinking, as a small web app you can install on a phone.

- **Today** shows the day's reading, what to look for, the news focus and the writing task, with that afternoon's news (about 1:30 pm IST): four stories, each with a question tied to the book you're reading.
- **History** lists every day so far as done or missed. Tap a day to open it.
- **Plan** shows the year's books by quarter, with dates and progress, plus the Sunday spiritual thread.
- Ticks are saved on the phone. The app opens offline and shows the last news it loaded.

## Files

| File | Purpose |
|---|---|
| `index.html` | The app |
| `plan.json` | The 364-day plan: `[book, quarter, read, look for, news focus, write]` per day, from `start` |
| `news.json` | Daily news picks, keyed by date; a scheduled Claude task adds each day's picks |
| `manifest.webmanifest`, `sw.js`, `icons/` | Make the app installable and let it open offline |

Chapter splits are approximate, since page counts differ between editions.
