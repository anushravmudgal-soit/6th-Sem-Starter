# Project Name: [Insert Project Name Here]
### Team ID: [e.g., Group-05]

## 🏢 Corporate Simulation Guidelines
**Approved by:** Mr.Anushrav Mudgal  
**Objective:** To develop a production-grade software solution using industry-standard DevOps and Agile methodologies.

---

## 👥 The Team & Responsibilities

| Role | Name | GitHub Username | Primary Responsibility |
| :--- | :--- | :--- | :--- |
| **Scrum Master / Lead** | [Name] | [@user] | Agile Process, Board Health & Approvals |
| **Backend Developer** | [Name] | [@user] | API Logic, Security & Server Ops |
| **Backend Developer** | [Name] | [@user] | API Logic, Database Integration |
| **Frontend Developer** | [Name] | [@user] | UI/UX, State Management & API Consumption |
| **Frontend Developer** | [Name] | [@user] | UI/UX, Client-side Validation |
| **DB & QA Specialist** | [Name] | [@user] | Schema Design, Testing & Documentation |

### 🛠 Role Descriptions

#### **1. Scrum Master / Team Lead**
* **Agile Management:** Owns the GitHub Project Board. Every task must have an owner and a priority.
* **Sprint Planning:** Leads bi-weekly meetings in Discord to move tasks from `Backlog` to `Todo`.
* **Blocker Removal:** Monitors `#attendance-logs` to identify and resolve team bottlenecks.
* **Merge Authority:** Performs final quality checks on all Pull Requests (PRs) before merging to `main`.

#### **2. Backend Developers**
* **Core Logic:** Building RESTful APIs and server-side business logic.
* **Data Security:** Implementing JWT/Session Auth and preventing SQL Injections.
* **Optimization:** Ensuring fast database queries and clean API responses.

#### **3. Frontend Developers**
* **UI/UX Implementation:** Translating requirements into responsive HTML/CSS/JS components.
* **Integration:** Connecting the frontend to backend APIs using `Fetch` or `Axios`.
* **Usability:** Ensuring the application is intuitive and bug-free on the client side.

#### **4. Database & QA Specialist**
* **Data Architecture:** Designing the ER Diagram and maintaining the SQL/NoSQL schema.
* **Quality Assurance:** Manually testing all features on the `dev` branch to identify bugs.
* **Technical Writing:** Managing the `/docs` folder (SRS, System Design, Test Reports).

---

## 🚀 WEEK 1: MANDATORY SETUP CHECKLIST
*Must be completed by the end of Week 1.*


### 1. Initialize Agile Project Board
1. Go to the **Projects** tab of this repository.
2. Click **"New project"** -> Select the **"Templates"** tab.
3. Choose the **"6th-Sem-Starter"** template from the Organization list.
4. Link this repository to that project so Issues appear automatically.
5. Populate the **Backlog** with at least 10 initial tasks (Modules, Database Design, Research).

### 2. Discord Sync & Identity
1. **Change Nickname:** Set your nickname in the Discord server to `Real Name | Role`.
2. **First Stand-up:** Post your first update in `#attendance-logs` (format: Yesterday/Today/Blockers).
3. **Team Hub:** All technical decisions must be recorded in your private `#team-chat` channel.
---


### 3. Submission of Synopsis
Upload your initial Project Synopsis PDF to the `/docs` folder for approval by the Professor.

---

## 🛠 Project Management (Agile)
We use **GitHub Projects** for task tracking.
* **The Golden Rule:** *If a task is not on the Board, it does not exist.*
* **Priority Tags:** Use `🔴 High`, `🟡 Medium`, and `🟢 Low` to categorize your tasks.
* **Categories:** Label every task as `Backend`, `Frontend`, `Database`, `Docs`, or `Bug`.

---

## ⚙️ Development Workflow (Git Flow & CI/CD)
We strictly follow **Branch Protection Rules**. Direct pushes to `main` are **FORBIDDEN**.

### 1. Branching Strategy
* `main`: Production-ready code. (Protected: No direct commits).
* `feature/feature-name`: Working branch for a specific task.
    * *Example:* `feature/login-validation`, `fix/navbar-css`

### 2. CI/CD (The Quality Gate) 🤖
Every push to a branch triggers an **Automated Syntax Checker (GitHub Action)**.
* **Yellow Circle 🟡:** Robot is checking your code.
* **Red X ❌:** Syntax error found. **DO NOT OPEN A PR** until this is fixed.
* **Green Check ✅:** Code is clean and ready for Peer Review.

### 3. The Development Cycle
1. **Pull** latest changes: `git pull origin main`
2. **Create** a branch: `git checkout -b feature/my-task`
3. **Code** & Push: `git push origin feature/my-task`
4. **Open Pull Request (PR):**
    * Tag a teammate as a **Reviewer**.
    * Mention the specific **Project Board Task** the PR resolves.
    * **Review Requirement:** At least 1 teammate must approve the code before it can be merged.

---

## 📝 Coding Standards
* **Commits:** Must be descriptive (e.g., `✅ Added JWT authentication middleware`).
* **Clean Code:** No hardcoded passwords/API keys. Use `.env` files.
* **Documentation:** All functions must have basic comments explaining their purpose.

---

## 📊 Evaluation & Attendance
Grading is based on your **Digital Footprint** in this repository and Discord.
1. **GitHub Insights:** Contribution graphs will verify individual coding effort.
2. **Project Board Velocity:** We will check if tasks are being moved daily or dumped last minute.
3. **Discord Presence:** Active participation in team voice channels and daily stand-ups is mandatory.

---



## 💻 Technical Setup
1. Clone the repo: `git clone [URL]`
2. Install dependencies: `[Command]`
3. Run the App: `[Command]`



