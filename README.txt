DAYMARK 4.0 — THREE-COLOR EDITION
====================================

Built for iPhone and MacBook as a free, installable web app.
Minimalist interface, no account, no paid subscription.

FEATURES
- Inbox, Today, Upcoming, All Tasks and Completed
- Projects, project sections and List / Board project views
- Monthly Calendar; tap a day to see its scheduled tasks
- Add, edit, complete, restore or delete tasks
- Descriptions, priorities, planned dates and times, subtasks, labels
- Separate hard deadlines (final cutoff date) alongside planned work dates
- Deadline badges, missed deadline alerts while using the app, Deadline overview
- Deadline filters: missed, due within 7 days, and no deadline
- Repeat: every day, weekday, week, month or year
- Filters: overdue planned dates, priority, no planned date, deadlines, and labels
- Search across tasks, notes, projects, labels and subtasks
- Insights: completion history and recent activity
- Light and dark themes
- Quick Add examples: "Call mum tomorrow @personal p1", "Pay rent every month"
- Export and import JSON backups
- Offline access after the website has been successfully loaded and cached

IMPORTANT LIMITATIONS
- Not the full Todoist service: no automatic cross-device sync, accounts,
  collaboration, assignments, push reminders, attachments, voice assistant,
  integrations, or complex natural-language dates.
- The time field is for planning; it does NOT send a notification.
- Your tasks are stored in this browser/on this device only.
- Data may be erased if you clear the browser's site data or remove the app.
- GitHub Pages makes your APP CODE public, not locally saved task entries.
  Never upload a task-data backup to GitHub.
- You can copy tasks between iPhone and MacBook via Settings > Export backup
  and Settings > Import backup. This is manual, not live sync.

INSTALL OR UPDATE YOUR EXISTING APP (IPHONE ONLY)
1. Download the ZIP, then open Files on your iPhone and unzip it.
2. In Safari, open: https://github.com/dulle-enke/personal-hub
3. Make sure the branch selector shows main.
4. Choose Add file > Upload files (you may need Safari's desktop site).
5. Choose these FIVE files from the unzipped folder (NOT the ZIP itself):
     index.html
     sw.js
     manifest.webmanifest
     icon-192.png
     icon-512.png
   Add README.txt too if you want instructions stored in the repository.
6. Commit directly to main. If GitHub Pages is already enabled, your app will
   publish automatically. Otherwise go to repository Settings > Pages,
   choose Deploy from a branch / main / (root), then Save.
7. Open: https://dulle-enke.github.io/personal-hub/
8. Safari Share > Add to Home Screen > Add. Reopen the installed app.

IF THE OLD APP STILL SHOWS
- Check GitHub's index.html shows the new Daymark source.
- Refresh Safari, then quit/reopen the Home Screen app.
- Give GitHub Pages time to publish, then retry.
- Avoid clearing Safari site data without exporting a backup first.

EXISTING TASKS
- Daymark tries to import task data from the previous Personal Hub or
  Daymark v1 when stored under the same website origin. Save a backup first.
- Old stored data is not removed automatically.

This is an original personal task manager, not affiliated with Todoist.

UPGRADE NOTE
- This version uses the existing daymark-tasks-v2 storage key; existing tasks are
  migrated without losing data. All pre-existing deadlines start blank.
- A deadline is a visual cutoff and filter, not a push notification.
- To set one, edit any task and fill in Deadline under the planned date.
- Existing tasks/sections/projects remain intact after updating the five files.

FEATURES THAT ARE NOT IN DAYMARK 3.0 (COMPARED WITH TODOIST)
- Automatic live syncing between iPhone and MacBook
- Background push/email/location reminders and scheduled notifications
- Shared projects, task assignments, team workspaces and collaboration
- Task comments, attached files, cloud attachment storage, external integrations
- iPhone widgets, Siri/Shortcuts integration, voice-based capture
- Advanced natural-language date parsing, custom query language, templates
- Task durations, nested sub-projects, drag-and-drop ordering, table view
- Secure account login/cloud backups (backups are manual JSON downloads)

These features need additional development and some require external services.


DAYMARK 4.0 — APPEARANCE UPDATE
- Your requested brand colors are blue #3969ac, yellow #f2b701, and green #11a579.
- Blue = main actions / navigation; yellow = priorities / deadlines; green = completion and progress.
- Same tasks, projects, and deadlines as Daymark 3.0. No new sign-in or syncing features.
- The app continues using the same local storage key so your tasks are preserved.
- Existing project colors are mapped into the three-color palette on upgrade.
- Updated app icons, dark mode and cache version are included.
- Export a backup from Settings before replacing your GitHub files.
