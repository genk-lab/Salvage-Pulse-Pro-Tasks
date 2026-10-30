# Pulse Pro Task Dashboard

A modern visual tracking dashboard built for **Daily, Weekly, Monthly, and Yearly** task management with automatic cadence resets and permanent historical archiving.

Inspired by modular productivity boards like xTiles and Notion, Pulse Pro tracks not only task completion but also **completion rates**, **average time to completion**, **active time spent**, and **cycle-specific notes**.

---

## 🌟 Key Capabilities

### 1. Multi-Cadence Task Management
- **Daily Tasks**: Resets every calendar day at midnight (00:00).
- **Weekly Tasks**: Resets at the beginning of each calendar week (ISO week rollover).
- **Monthly Tasks**: Resets on the 1st of every month at midnight.
- **Yearly Tasks**: Resets annually on January 1st.

### 2. Live Metrics & Analytics
- **Completion Rate**: Calculated in real time per cadence and globally across all active tasks.
- **Average Time to Completion**: Dynamically tracks the average duration (in minutes or hours) required to complete tasks.
- **Active Stopwatch & Manual Logging**: Includes a live one-click stopwatch (Start / Pause) per task as well as quick manual duration logging.
- **Cadence Health Summary**: At-a-glance health breakdown for Daily, Weekly, Monthly, and Yearly loops.

### 3. Automatic Refresh with Historical Preservation
- **Non-Destructive Rollovers**: When a cycle expires (e.g. midnight arrives), the active period is automatically locked and preserved in the **Historical Archive**.
- **Historical Explorer & Time Machine**:
  - Filter and inspect any past day, week, month, or year.
  - View exact historical completion rates, average time to completion, and all completed vs. missed tasks.
  - Review notes written during that specific historical period.
- **Live Countdown**: Displays a countdown indicator showing exact hours, minutes, and seconds until the next daily reset.

### 4. Per-Period Notes & Context Logging
- Click the **Notes / + Note** button on any task card to log decisions, reflections, blockers, or links.
- Notes are permanently saved with that cycle's historical record upon refresh.

### 5. Data Portability & Testing Tools
- **Instant JSON Export & Import**: Backup your entire board, templates, active periods, and complete history to a single JSON file.
- **Rollover Simulation Engine**: Test the automatic rollover without waiting for midnight using the *"Simulate Daily Rollover"* and *"Simulate Weekly Rollover"* buttons in Settings (`⚙`).
- **xTiles Sync & Export**: One-click formatting of tasks into native xTiles interactive checklist blocks and tag structure.

---

## 🧩 Setting up in xTiles & Linking to Pages / Groups

### 1. Populating Tasks into xTiles
1. In Pulse Pro Task Dashboard, click the **`xTiles Sync`** button in the top navigation bar.
2. Select your desired cadence (e.g. *Daily Only*, *Weekly Only*, or *All Cadences*).
3. Click **"Copy for xTiles"**.
4. In your xTiles workspace, create a Tile block, click inside it, and press `Ctrl + V` (or `Cmd + V`).
5. xTiles will immediately convert the pasted markdown into native task checkboxes `[ ]`, duration pills `(30m)`, `#tags`, and sub-notes.

### 2. Linking Across Pages & Groups in xTiles
- **The `@` Mention Shortcut (Two-Way Links)**: Inside any task, note, or tile header in xTiles, type `@` followed by the name of any other document, page, or team member (e.g., `@Sprint Goals`, `@Marketing Campaign`, `@Q4 Budget`). Clicking the mention immediately jumps to that page, and xTiles logs the reciprocal backlink.
- **Paste as Linked Page (Cross-Project Real-Time Sync)**: Right-click your Tasks page in the tab bar or left panel, select **Copy**, open any other project group or workspace, right-click and choose **"Paste as Linked Page"**. Any changes or checkmarks made in one place update across every workspace.
- **Create Nested Subpages (`/page`)**: Type `/page` or press `9` on a new line inside any tile to create a clean nested subpage for extensive project briefs, retrospectives, or sprint documentation without cluttering your main canvas.
- **Centralized My Planner & Task Collection**: All tasks added to your xTiles tiles automatically feed into the global **Task Panel** (left sidebar), **My Planner**, and the database-style **Task Collection** table.

### 3. Embedding the Live Dashboard into xTiles
If you host `index.html` (e.g. via GitHub Pages, Vercel, or local tunnel):
1. In xTiles, hover over a tile and click `+` or type `/embed`.
2. Paste the URL of your Pulse Pro dashboard.
3. The interactive stopwatches, live completion rings, and historical time-travel explorer will run directly inside your xTiles canvas.

---

## 🚀 How to Run & Open

### Option 1: Open Directly in Your Web Browser
Simply double-click or open:
```
C:\Users\genni\.gemini\antigravity\scratch\Pulse Pro Task Dashboard\index.html
```
in Google Chrome, Microsoft Edge, Brave, or any modern browser.

### Option 2: Set as Active Workspace
To continue developing or adding features to this tracker inside Antigravity:
1. Set `C:\Users\genni\.gemini\antigravity\scratch\Pulse Pro Task Dashboard` as your active workspace directory in Antigravity.
2. Edit or expand `index.html` as needed.
