# Daily Planner
Daily Scheduler Web App

An interactive and feature-rich daily planner built using **HTML, CSS and JavaScript**. This scheduler allows users to plan their day from **6:00 AM to 6:00 PM**, store tasks per selected date, and even receive **notifications** before upcoming tasks. It also includes PDF export functionality.

🌟 Features
 1. 📅 **Date-Based Scheduling**
- Users select a specific date to view or create a personalized schedule.
- Each date's tasks are saved and retrieved using `localStorage`.

2. 💡 **Start Page**
- Two clear actions:
  - `Get Started`: Opens the scheduler for the selected date.
  - `Display Today's Plan`: Shows tasks already added for today in a neat list format.

3. ⏰ **Time Block Interface**
- Scheduler runs from **6 AM to 6 PM**.
- Each hour block includes:
  - Hour label
  - Textarea for input
  - Save button (checkmark) to store and visually strike through completed tasks.

4. ✅ **Extra Flexibility**
- A special "Other" section allows logging tasks that fall outside the fixed hours.

5. 🔔 **Notifications**
- Users receive **desktop alerts 5 minutes before a task** (if notifications are allowed).

6. 📤 **PDF Export**
- One-click export to PDF using jsPDF, capturing the current task list for the selected date.

7. 🧹 **Clear Tasks**
- A button to remove all scheduled tasks for the day.

