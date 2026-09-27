# Daily Proficiency

A phone-first web app for logging what you did each day, from when to when, shown as color-coded blocks on a timeline.

Live: https://nonidino.github.io/daily-proficiency/

- Tap **Log** (or tap an hour on the timeline) to add an entry; tap a block to edit or delete it.
- Or choose **Start now** in the Log sheet to run a timer, then tap **End** in the bottom bar. Only one timer can run at a time; starting another ends the current one at the new start time.
- Switch between **Day** and **Week** views. Week view is a 7-column calendar plus a weekly summary (total per type and average per day).
- Swipe left/right to change days (or weeks); tap the date to jump to any day.
- Data lives in your browser's local storage. On iPhone, use Share → Add to Home Screen, and export a backup from the ⋯ menu now and then.

Plain static files (`index.html`, `sw.js`, `manifest.webmanifest`, `icons/`) — no build step.
