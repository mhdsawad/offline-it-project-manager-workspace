# Offline IT Project Manager Workspace

A single-file, browser-based Project Manager workspace for managing **Fixed Bid / Waterfall**, **Agile Scrum / Time & Material**, and **Hybrid** IT projects from one place.

This initiative is intended as a community-friendly productivity tool for project managers who need a lightweight, offline-capable workspace for planning, execution control, budget tracking, team visibility, reporting, and AI-style project prediction.

> **Download:** Use the latest release asset named `index.html`, or open the live GitHub Pages demo after it is enabled.
>
> **GitHub Pages:** `https://github.com/daip85/offline-it-project-manager-workspace`
>
> **Latest Release:** `https://github.com/daip85/offline-it-project-manager-workspace`

---

## Why this tool exists

Project managers often manage multiple delivery models at the same time. Fixed bid projects may need WBS, baselines, dependencies, and Gantt controls. Agile or Time & Material projects may need backlog, sprint planning, Kanban, velocity, and burndown. Hybrid projects need both, with traceability between fixed deliverables and agile execution.

This tool brings those views together in one offline browser workspace.

---

## Key capabilities

### Delivery models

- **Fixed Bid / Waterfall** — WBS task management, Gantt planning, dependencies, baseline, critical path, budget and EVM-style controls.
- **Agile Scrum / Time & Material** — backlog, sprint board, Kanban workflow, story points, burndown, velocity and sprint health.
- **Hybrid** — both fixed-plan and agile views, with links between WBS deliverables and stories.

### Project management features

- All-project summary dashboard.
- Project-wise cockpit.
- Project-wise Gantt / WBS.
- Project-wise sprint board.
- Project-wise budget.
- Project-wise team/resources.
- Project-wise RAID and risk register.
- Project-wise reports.
- Project-wise AI Prediction.
- Overall summary AI Prediction.
- Master data / setup section.
- Detailed Help, Appendix, and Codebase Whitepaper.

### Reporting and charts

Includes a mix of basic and advanced chart concepts such as:

- Donut charts
- Bar charts
- Grouped bar charts
- Horizontal bar charts
- Line and area trends
- Radar charts
- Risk matrices
- Heatmaps
- Bubble charts
- Treemaps
- Funnel charts
- Waterfall charts
- Timelines
- Lollipop charts
- Dependency network visuals
- PMBOK-style project health views
- Agile burndown and velocity views

### AI-style prediction

The tool includes browser-based prediction logic. It is not a cloud AI service and does not call an external model. It uses local project data to highlight:

- Delivery confidence
- Schedule slippage risk
- Budget overrun risk
- Resource overload
- Critical path pressure
- Sprint risk
- Risk escalation
- Suggested PM actions

---

## How to use

### Option 1 — Download and run locally

1. Go to **Releases**.
2. Download `index.html` from the latest release.
3. Double-click the file or open it in a modern browser.
4. Start with sample data, then create your own projects.
5. Use backup/export before clearing browser data.

No installation, server, login, or internet connection is required after the file is downloaded.

### Option 2 — Use GitHub Pages

After the repository owner enables GitHub Pages, open:

`[ADD_GITHUB_PAGES_URL_HERE]`

The app still stores your working data locally in your browser.

---

## Browser support

Recommended browsers:

- Latest Google Chrome
- Latest Microsoft Edge
- Latest Mozilla Firefox
- Latest Safari

A desktop or laptop browser is recommended for the full Gantt, chart, and reporting experience. Mobile browsers can be used for quick review, but detailed planning works best on a larger screen.

---

## Data and privacy

- Data is stored locally in the browser on the user’s device.
- No server database is used.
- No login is required.
- No project data is sent to the repository owner.
- Clearing browser storage can remove saved project data.
- Use the tool’s export/backup option before switching browsers, devices, or clearing data.

---

## Files in this repository

| File | Purpose |
|---|---|
| `index.html` | The complete single-file PM workspace. |
| `docs/IT_PM_User_Guide_with_Screenshots.pdf` | Detailed user guide with screenshots and workflow explanations. |
| `prompts/IT_PM_Generation_Prompt.txt` | Rebuild/enhancement prompt for GenAI tools. |
| `README.md` | Repository overview and usage instructions. |
| `LICENSE` | License terms. |
| `CONTRIBUTING.md` | Contribution guidelines. |
| `SECURITY.md` | Security and privacy reporting guidance. |
| `CHANGELOG.md` | Release history. |

---

## Suggested workflow for new users

1. Open the tool.
2. Review the **All Projects Summary**.
3. Create a project and select the operating model:
   - Fixed Bid / Waterfall
   - Agile Scrum / Time & Material
   - Hybrid
4. For fixed bid projects, create WBS tasks and review the Gantt plan.
5. For agile projects, create backlog items, sprints, and update the Kanban board.
6. Add project budget, team members, risks, and RAID details.
7. Review project-wise reports.
8. Review AI Prediction for delivery confidence and recommended actions.
9. Export backup regularly.

---

## Important disclaimer

This is a generic community tool for IT project management. It is not affiliated with Microsoft, Atlassian, PMI, Scrum.org, or any other vendor or certification body. It does not replicate proprietary corporate templates, formats, data structures, dashboards, or naming conventions. PMBOK, Agile, Scrum, Kanban, Waterfall, Gantt, EVM, and similar concepts are used as general project management references.

The AI-style prediction feature is a local rule-based analytical assistant. It should support PM judgment, not replace professional governance, contractual review, risk management, or executive decision-making.

---

## Contributing

Community improvements are welcome. Please read `CONTRIBUTING.md` before submitting changes.

Useful contribution areas:

- UI responsiveness improvements
- Additional charts
- Accessibility enhancements
- More formulas in the appendix
- Better sample data
- Localization
- More export options
- Additional project report templates

---

## License

See `LICENSE`.

Suggested default: MIT License for the HTML/source code. Documentation can also be shared under the same license, or under a Creative Commons license if preferred by the repository owner.

