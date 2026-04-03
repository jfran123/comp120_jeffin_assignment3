# comp120_jeffin_assignment3
COMP120_jeffin_versioncontrol
# TaskFlow 📝

A simple, clean task manager application to help you organize, prioritize, and track your daily tasks.

## Features

- ✅ Create, edit, and delete tasks
- 📁 Organize tasks into categories/projects
- 🏷️ Add tags and priority levels (Low, Medium, High)
- 📅 Set due dates and reminders
- 🔍 Search and filter tasks
- 📊 Progress tracking dashboard
- 🌙 Dark mode support
- 💾 Local storage persistence

## Demo

![TaskFlow Screenshot](screenshots/dashboard.png)

> Live demo: [https://taskflow-demo.netlify.app](https://taskflow-demo.netlify.app)

## Getting Started

### Prerequisites

- Node.js v18 or higher
- npm v9 or higher

### Installation

1. Clone the repository:
```bash
   git clone https://github.com/yourusername/comp120_yourname_assignment3.git
   cd comp120_yourname_assignment3
```

2. Install dependencies:
```bash
   npm install
```

3. Start the development server:
```bash
   npm run dev
```

4. Open your browser and navigate to `http://localhost:3000`

## Usage

### Adding a Task

1. Click the **+ New Task** button in the top right
2. Enter a task title and optional description
3. Set a due date, priority level, and category
4. Click **Save** to add the task to your list

### Managing Tasks

- **Complete a task** — click the checkbox next to any task
- **Edit a task** — click the pencil icon or double-click the task title
- **Delete a task** — click the trash icon (confirmation required)
- **Filter tasks** — use the sidebar to filter by status, priority, or category

### Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `N` | New task |
| `E` | Edit selected task |
| `Delete` | Delete selected task |
| `Space` | Toggle task complete |
| `Ctrl + F` | Search tasks |
| `/` | Focus search bar |

## Project Structure
comp120_yourname_assignment3/
├── src/
│   ├── components/        # UI components
│   │   ├── TaskCard.js
│   │   ├── TaskForm.js
│   │   └── Sidebar.js
│   ├── pages/             # Application pages
│   │   ├── Dashboard.js
│   │   └── Settings.js
│   ├── utils/             # Helper functions
│   │   ├── storage.js
│   │   └── dateHelpers.js
│   └── App.js
├── public/
│   └── index.html
├── tests/
│   └── taskManager.test.js
├── .gitignore
├── package.json
└── README.md
## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit: `git commit -m "Add: your feature description"`
4. Push to your branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

Please make sure your code passes all existing tests before submitting.

## Running Tests
```bash
npm test
```

## Built With

- [React](https://react.dev/) — Frontend framework
- [localStorage API](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) — Data persistence
- [date-fns](https://date-fns.org/) — Date formatting and utilities
- [Tailwind CSS](https://tailwindcss.com/) — Styling

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- Email: yourname@example.com

---

*COMP120 — Version Control Assignment | comp120_yourname_versioncontrol*
