# Credit_Compass.github.io

🧭 Credit Compass
Loan Collection System - Client Status Tracker
A web-based loan collection management system built for lending companies handling SSS and GSIS pensioner accounts. Credit Compass helps staff monitor client payment statuses, coordinate field visits, assign agent tasks, and maintain complete client records, all from a single browser-based dashboard with no installation required.
---

🌐 Live App
Deploy your own instance using the setup guide below. Runs entirely on GitHub Pages + Google Sheets, no server needed.
---

✨ Features 📊 Dashboard
- Real-time stat cards — Total Clients, Updated, Overdue, Delinquent, Needs Action
- Four charts — Client Status (Pie), Payment Status (Bar), Monthly Trends (Line), Clients per Branch (Bar)
- Branch summary table with full breakdown per branch
- Client directory with search and filters by payment status, client status, and branch
- Print reports that respect active filters — prints exactly what is on screen
- CSV export of all client records

👤 Client Management
- Add, edit, and delete client records
- Full client profile page — click any client row to open a dedicated page showing all loan details, pension info, contact info, co-maker, spouse, photos, and follow-up log
- Three photo uploads per client — client photo, house sketch, co-maker photo (via Imgur API)
- Problem code tracking
- Edit and Delete buttons directly inside the profile page

📝 Follow-up Logs
- Per-client log entries — Visit, Call, or Note types
- Add logs from both the right panel and the full client profile page
- Log shows date, type, staff name, and note text

🗓 Visit Scheduling
- Schedule field visits per client with date, time, purpose, assigned staff, and notes
- Mark visits as Done
- Upcoming visits visible in the Schedule Visit modal

🔔 Notifications
- Three groups — Scheduled Visits (within 2 days), Overdue Clients, Delinquent Clients
- Click any notification to jump directly to that client
- Unread indicators with badge count on topbar

📅 My Calendar
- Monthly calendar view with color-coded task chips per day
- Five task types — Collection Visit, Follow-up Call, Field Visit, Barangay/Legal Action, Demand Letter
- Click any day to add or view tasks
- Browser push notifications — reminds you 1 day before each task
- Auto-creates a Gmail draft when a task is saved

🧑‍💼 Field Agent Schedule
- Add and manage real field agents (completely separate from system login users)
- Assign custom tasks to agents — Go to Bank, Assist Client, Collect Payment, Deliver Documents, etc.
- Per-task status — Pending or Done
- Add remarks per task after completion
- Filter by task status and date period
- All agent data saved to Google Sheets FieldAgents tab

🔐 Login System
- Username and password login form
- Show/hide password toggle
- Press Enter to sign in
- Role-based access — Admin and Staff
- 10-minute idle auto-logout
- Session restore on page reload

📋 Audit Log (Admin only)
- Full history of every action — logins, views, edits, deletions, prints, exports
- Opens in a separate printable window

⚙️ Settings (Admin only)
- Change Google Apps Script URL without redeploying
- Update passwords for all 6 user accounts
