# Sy Phany Guo — Personal Portfolio Website
**ISDS 4125: Analysis and Design of Information Systems — Fall 2026**  
**Instructor:** Dr. Gabriele Piccoli | Louisiana State University (E. J. Ourso College of Business)

---

## 🌐 Live Website & Repository
* **Live Website URL:** [https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/](https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/) *(Update with your GitHub Pages URL after publishing)*
* **GitHub Repository:** [https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME)

---

## 📌 Project Overview
This website is a professional personal portfolio built for ISDS 4125 using a **hybrid layout** with a **custom ocean palette** (marine navy, coastal cyan, and seafoam teal). The content is strictly authentic and grounded in my academic studies at Louisiana State University, real work experience, and technical competencies.

### Key Structure & Files
1. **`index.html` (Landing Page — Single-Page Architecture):**
   * **Profile / Hero:** Clean typographic hero highlighting LSU Information Systems & Analytics degree and career summary.
   * **About / Background:** Summary of academic focus, coursework (Design of Information Systems, Business Statistics, Data Mining, Accounting Analytics, Data & Information Management), and bilingual capability (Mandarin Chinese & English).
   * **Skills & Competencies:** Categorized skills across Software (PowerBI, Tableau Software, Claude Code, Google Workspaces, Microsoft Office, 20-20 Design), Technical (Python, SQL, Github, Data Visualization, Data Warehousing, Risk Analysis), and Operations (BOM, Purchase Orders, Vendor Sourcing).
   * **Experience / Jobs Held:** Chronological records of positions at Assurant (Auto Risk Analyst), Formula SAE at LSU TigerRacing (Treasurer & Financial Analyst), and Grabince Industrial LLC (Assistant Project Manager).
   * **Contact:** Direct channels (email, phone, LinkedIn, location).
2. **`resume.html` (Dedicated Resume Page):**
   * Formal, printable digital resume directly mirroring my resume with print-optimized styles (`@media print`) and instant **Print / Save as PDF** functionality.
3. **`project.html` (Dedicated Project Showcase Page):**
   * Deep-dive case study on the **AI-Driven QBR Automation & Auto Risk Analysis** initiative, detailing auto manufacturer warranty predictions, high-risk dealer identification, and Claude Code AI skill development cutting deck preparation from 1 day to 10 minutes.
4. **`styles.css` (Shared Design System):**
   * Consistent ocean theme (`#050e1a`, `#0a182d`, `#142f54`) with coastal cyan (`#06b6d4`), seafoam (`#14b8a6`), and sky blue (`#38bdf8`) accents, responsive navigation, and mobile-friendly layouts.

---

## 💡 Learning & Vibe Coding Reflection
*During the vibe coding process with Google Antigravity, I initially did not understand why the navigation bar links on `project.html` and `resume.html` used absolute anchor references like `index.html#skills` and `index.html#experience`, whereas `index.html` used local fragments like `#skills` and `#experience`. I asked the agent to explain why the link structure differed between files. The agent explained that because each HTML file operates as an independent document in the browser, an anchor like `#skills` only works when you are already on `index.html`; navigating back to that section from a separate page requires directing the browser to the file first (`index.html#skills`). Understanding this helped me appreciate how hybrid web architectures balance single-page scrolling with multi-page navigation.*

---

## 🚀 How to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git
   ```
2. Open the project folder in **Google Antigravity IDE** or any code editor.
3. Preview the site by opening `index.html` directly in any web browser, or launch a lightweight local server:
   ```powershell
   npx http-server . -p 8080
   ```
4. Access `http://localhost:8080` in your browser.
