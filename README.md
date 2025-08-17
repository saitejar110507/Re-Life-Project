# 🌱 Re-Life  
**Your Personal Management / Life OS Web App**  
*A modular productivity, health, habit, and knowledge management system powered by HTML, CSS, JavaScript, and Google Sheets.*

---

## 📌 Overview  
**Re-Life** is a **Personal Management / Life OS Web App** that combines productivity, habit tracking, health logging, study planning, journaling, and knowledge management — all in one unified dashboard.  

It is designed to be:  
- **Lightweight & Modular** (HTML, CSS, JS front-end)  
- **Data-Driven** (Google Sheets as backend database)  
- **Customizable & Extendable** (modular system with themes, charts, and personal preferences)  

---

## 🚀 Core Features  

### 🏠 Dashboard  
- Today’s tasks, calendar, quick overview of goals.  
- Quick add buttons → new task, journal entry, health log.  
- Motivational quote of the day (API or preloaded).  

### ✅ Tasks & Projects (Ultimate Tasks style)  
- Task manager with **priorities, due dates, recurring tasks**.  
- Project → tasks relationship.  
- **Kanban view** + List view.  
- “Today” and “Next 7 Days” filters.  
- Progress tracking (% per project).  

### 🎯 Goals (Short / Medium / Long Term)  
- Database of goals by time horizon.  
- Link goals ↔ projects ↔ tasks.  
- Automatic progress rollups.  

### 🔁 Habits & Routines  
- Daily / weekly / monthly habit tracker.  
- Visualizations: streaks, heatmaps, progress charts.  
- Habits can link directly to goals.  

### 🏋️ Health & Fitness Hub  
- Track workouts, meals, meds, symptoms.  
- Progress charts (weight, exercise, calories).  
- Quick log buttons for common actions.  

### 📚 Study & Skill Development (Student OS style)  
- Track courses, assignments, exams, certifications.  
- Reading log + study planning view.  
- Link study progress to goals.  

### 📝 Daily Journal & Personal Diary  
- Auto-stamped journal entries.  
- Morning/evening reflection prompts.  
- New page per day option.  
- Entries linked to tasks/goals of the day.  

### 🧠 Knowledge & Notes (Siyuan / Foam / Dendron style)  
- Markdown editor for structured notes.  
- Hierarchical organization.  
- Graph view of connected notes (Obsidian style).  
- Full-text search.  
- Local-first + Google Sheets/Drive sync.  

### 🎨 Theme & Personalization  
- Light / Dark / System themes.  
- Extra modes: Minimal, Professional, High Contrast.  
- Fun modes: Anime, Cartoon, Motivational.  
- Preferences saved in localStorage.  

### 📊 Data Visualization & Insights  
- Chart.js graphs for:  
  - Tasks completed vs pending  
  - Habit streaks & success rates  
  - Health & fitness logs  
  - Study time tracking  
- Customizable dashboard widgets.  

### 🔍 Smart Features  
- Global search across tasks, notes, goals, journal.  
- (Future) AI insights → summarize journals, suggest habits/tasks.  

---

## ⚙️ Technical Details  
- **Front-end**: HTML, CSS, JavaScript (responsive, minimal UI).  
- **Backend**: Google Sheets as database.  
- **Storage**:  
  - LocalStorage → user settings & themes.  
  - Google Sheets → all structured data.  
- **Data Model**: Each module (Tasks, Goals, Habits, Health, Study, Journal, Notes) maps to its own Sheet tab.  
- **Charts**: Chart.js (or similar).  

---

## 🌟 Bonus / Future Roadmap  
- Google login (OAuth).  
- Export/import (CSV, JSON, Markdown).  
- AI integration for summaries & recommendations.  
- Offline-first with **PWA support**.  

---

Re-Life/
│── index.html # Dashboard
│── /css # Styles
│── /js # Core scripts + modules
│ ├── tasks.js
│ ├── goals.js
│ ├── habits.js
│ ├── health.js
│ ├── study.js
│ ├── journal.js
│ ├── notes.js
│── /assets # Icons, images, themes
│── /charts # Chart.js configs
│── README.md # You are here



---

## 🛠️ Setup & Usage  

1. **Clone the repo**  
   ```bash
   git clone [https://github.com/saitejar110507/Re-Life-Project/]
   cd Re-Life


## 📂 Project Structure (Planned)  


Re-Life/
│── index.html # Dashboard
│── /css # Styles
│── /js # Core scripts + modules
│ ├── tasks.js
│ ├── goals.js
│ ├── habits.js
│ ├── health.js
│ ├── study.js
│ ├── journal.js
│ ├── notes.js
│── /assets # Icons, images, themes
│── /charts # Chart.js configs
│── README.md # You are here


2. Connect Google Sheets backend

Create a Google Sheet with tabs: Tasks, Goals, Habits, Health, Study, Journal, Notes.

Use Google Apps Script API or Sheet API to enable CRUD operations.

Add your API key in /js/config.js.

3. Open index.html in browser

Start using your Life OS dashboard!

# 🙌 Contributing

Contributions are welcome! Feel free to:

Open issues (feature requests, bugs).

Submit PRs for improvements.

Share new ideas for modules/themes.

# Cpoy right issues 

"All rights reserved. Please give proper attribution if using or adapting any part of this project. Unauthorized use, resale, or distribution of the source code is prohibited and may result in legal consequences."
