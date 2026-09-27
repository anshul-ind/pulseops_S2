# ⚡ PulseOps

PulseOps is a full-stack engineering workspace designed to bring project activity, team communication, repository data, integrations, tasks, tickets, reports, and analytics into one centralized workspace.

The platform connects engineering tools such as **GitHub, Slack, and Jira** so teams can keep their development workflow organized and accessible from a single interface.

---

## 🌐 Live Demo

**[Open PulseOps](https://amenses-new-pulseosp.vercel.app/)**

<img width="1919" height="992" alt="Screenshot 2026-09-27 162216" src="https://github.com/user-attachments/assets/afd3b479-aa8d-4b0c-89a9-6b7d17408be7" />


## 📌 Overview

PulseOps is built as a centralized engineering operations workspace.

Instead of switching between multiple tools to check repositories, team communication, Jira issues, and project activity, PulseOps brings these workflows together inside a workspace-based interface.

The application includes dedicated sections for:

- Workspace overview
- Repository management
- Team communication
- Reports
- Analytics
- Developers
- Tasks
- Tickets
- Third-party integrations
- Workspace customization

---

## ✨ Features

### 🏢 Workspace Management

PulseOps uses workspaces to organize engineering activity and project information.

Each workspace provides a centralized environment for connected repositories, communication, reports, tasks, tickets, and team activity.

---

### 🔗 Third-Party Integrations

PulseOps provides integration support for major development and collaboration platforms.

Currently represented in the application:

- **GitHub** — synchronize repositories and track pull requests
- **Slack** — bring team conversations into PulseOps
- **Jira** — synchronize Jira issues and project activity

The integrations page provides connection status and integration management controls.

---

### 💬 Team Communication

The Communication section brings connected Slack conversations into the PulseOps workspace.

Teams can view synchronized channel conversations directly inside the application without leaving the workspace.

---

### 🎨 Workspace Customization

PulseOps includes workspace-level customization options.

Users can configure:

- Workspace accent color
- Light theme
- Dark theme
- System theme

Available accent themes include:

- Violet
- Deep Blue
- Teal
- Emerald
- Rose
- Amber
- Purple
- Slate

---

### 📊 Reports & Analytics

PulseOps provides dedicated areas for viewing project and engineering information through reports and analytics.

These sections are designed to provide a centralized view of activity across connected engineering workflows.

---

### 👨‍💻 Developer Workspace

The Developers section provides a dedicated area for engineering-related workspace information and activity.

---

### ✅ Tasks & Tickets

PulseOps provides separate workspace sections for managing engineering tasks and tickets.

This keeps work tracking accessible alongside repositories, communication, and integrations.

---

### 🤖 AI-Assisted Insights

The project includes AI-powered summary functionality for transforming workspace information into useful engineering insights.

The repository also contains implementation work around AI summaries and related workspace panels.

---

## 🖥️ Screenshots

### 🎨 Workspace Customization

Configure the workspace appearance, accent color, and display theme.
<img width="1919" height="1048" alt="Screenshot 2026-09-27 160853" src="https://github.com/user-attachments/assets/7b80b16c-dc6d-43de-bf61-d7551b99e613" />


### 🔗 Integrations

Connect and manage GitHub, Slack, and Jira integrations from one place.
<img width="1919" height="989" alt="Screenshot 2026-09-27 132712" src="https://github.com/user-attachments/assets/91e94bf5-e664-4e46-b74a-613b0fde9e82" />

### 💬 Team Communication

View synchronized Slack workspace conversations directly inside PulseOps.
<img width="1903" height="991" alt="Screenshot 2026-09-27 132643" src="https://github.com/user-attachments/assets/5cec9840-d4cc-4adb-ac89-fcdcf6be8995" />



<img width="1910" height="984" alt="Screenshot 2026-09-27 132610" src="https://github.com/user-attachments/assets/6e8496fc-0386-4d63-ba70-cd9ca778fc61" />


## 🛠️ Tech Stack

### Frontend

- Next.js
- React
- NextAuth.js
- Role-Based Access Control (RBAC)

### Backend

- Node.js
- Express.js

### Database

- MongoDB Atlas
- Mongoose

### APIs & Services

- GitHub integration
- Slack integration
- Jira integration
- Gemini API
- Nodemailer
- Joi validation

### Deployment

- Vercel

---

## 🏗️ Project Structure

```text
PulseOps/
│
├── App/
│   └── workspace/
│       └── [workspaceId]/
│           └── integrations/
│
├── client/
│   ├── components/
│   ├── pages/
│   └── ...
│
├── server/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── ...
│
├── scripts/
│
├── .vscode/
│
├── .gitignore
├── migrate-jira-issue-index.js
├── opencode.json
└── README.md<img width="1919" height="992" alt="Screenshot 2026-09-27 162216" src="https://github.com/user-attachments/assets/0ab53eeb-6ff2-4931-ae7b-28e0c875f9b7" />
