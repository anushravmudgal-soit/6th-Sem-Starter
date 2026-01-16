# Project Name: [Insert Project Name Here]
### Team ID: [e.g., Group-05]

## 🏢 Corporate Simulation Guidelines
**Approved by:** Prof. Anushrav Mudgal
**Objective:** To develop a production-grade software solution using industry-standard DevOps and Agile methodologies.

---

## 👥 The Team
| Role | Name | GitHub Username | Primary Responsibility |
| :--- | :--- | :--- | :--- |
| **Team Lead** | [Name] | [@user] | Architecture & Merge Approvals |
| **Developer** | [Name] | [@user] | Backend / API |
| **Developer** | [Name] | [@user] | Frontend / UI |
| **Developer** | [Name] | [@user] | Database & Testing |
| **DevOps** | [Name] | [@user] | CI/CD & Documentation |

---

## 🚀 WEEK 1: MANDATORY SETUP CHECKLIST
*All teams must complete these steps by the end of Week 1 to receive project approval.*

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
