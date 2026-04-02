# ProLog - Release Tracker & Changelog Engine

ProLog is an advanced, beautifully styled client-side release tracking and changelog generation engine designed for developers to manage deployment manifests, semantic versions, and staging queues efficiently. 

**🔴 Live Demo / Application:** [https://helloarman.github.io/prolog](https://helloarman.github.io/prolog)

---

## 🚀 Key Features

*   **Repository Provisioning:** Start tracking software repositories with ease by defining base versions and maintaining release guidelines.
*   **Semantic Versioning:** Automatically calculates and steps major, minor, or patch versions based on commit logs categorized by `Breaking`, `Feature`, `Bug Fix`, `Update`, or `Improvement`.
*   **Staging Queue Management:** Create, edit, and safely delete pre-release logs before officially committing them to a deployed release.
*   **Robust Export Options:** Export your professional changelogs as `.txt`, selectable text `.pdf`, or stunning, shareable Professional Images!
*   **Local-First & Import/Export Engine:** Everything runs safely in your browser via LocalStorage. You can export complete project workflows as JSON backups and import them intelligently across different devices.
*   **Dashboard Insights:** Track pending commits, current deployment metrics, and distribution matrix summaries directly from the dashboard.

## 💻 Tech Stack
- Frontend Dashboard: Vanilla HTML5 / Javascript
- Framework: Tailwind CSS via CDN 
- Assets: Lucide Icons, jsPDF, html2canvas

## 🛠 Usage
This app is entirely client-side. To run it locally:
1. Clone the repository.
   ```bash
   git clone https://github.com/helloarman/prolog.git
   ```
2. Open `index.html` in your favorite modern browser.
3. Provision your first repository from the "Active Projects" sidebar!

## 📜 Exporting & Importing Workloads
- At any given time, you can secure your active project repository by clicking **Export Backup File** to securely download it as a JSON payload.
- To use your payload on another device, hit the **Import/Update Backup File** at the bottom of the navigation sidebar. The engine will accurately parse timestamps to ensure you aren't accidentally downgrading your files!

## 🤝 Developed By

Designed and developed by **[Arman](https://github.com/helloarman)**.

If you enjoy this tool, don't forget to star the repository!
