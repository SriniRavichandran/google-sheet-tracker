# 4iApps 3D Google Sheets Tracker & Habit Suite

Full-featured 3D Glassmorphic Google Sheets Workspace supporting both Daily Activity Management and Habit Tracking.

## Features

### 📅 Activity Planner Mode ("Daily Activity Planner", "Daily Focus", "Manage Conflict")
- **3D / Glass UI**: Modern dark theme with glowing accents and perspective cards.
- **Time Slot & Date Grid**: Interactive schedule matrix.
- **Cell Operations**: Click to edit activity details, clear cells, add/delete time rows and date columns.
- **Search & Filter**: Real-time searching across activities.

### 🔥 Habit Tracker Mode ("Habit Tracker")
- ✅ **Daily Tick / Checkmark Grid**: One-click status cycling (🟢 Completed / 🔴 Missed / ⏸️ Skipped / ⚪ Blank).
- 📅 **Automatic Date Columns**: Auto-generated 1..31 days with weekdays (Mon, Tue...) and highlight on **TODAY**.
- 📊 **Completion Dashboard**: Overall completion rate %, weekly progress breakdown, and today's status badges.
- 🔥 **Current & Best Streaks**: Live streak algorithms calculating active consecutive days and all-time records per habit.
- 📆 **Month Selector**: Dynamic Year & Month picker (e.g. August 2026).
- 📝 **Habit Date Notes**: Right-click or note icon to open journal entries and reflections for specific habit dates.

### 🔄 Google Sheets Sync & Local Mode
- **Google OAuth Login**: Real-time read/write synchronization with Google Sheets API.
- **Local / Offline Fallback**: Instant local storage caching with pre-configured demo habits and schedules.

---

## Configuration

In `index.html`:
- `GOOGLE_CLIENT_ID` = your Google OAuth Client ID
- `GOOGLE_SHEET_ID` = your Google Spreadsheet ID
