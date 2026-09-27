# Sy Phany Guo — Personal Portfolio Website
**ISDS 4125: Analysis and Design of Information Systems — Fall 2026**  
**Instructor:** Dr. Gabriele Piccoli | Louisiana State University (E. J. Ourso College of Business)

---

## 🌐 Live Website & Repository
* **Live Website URL:** [https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/](https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/) *(Update with your GitHub Pages URL after publishing)*
* **GitHub Repository:** [https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME)

---

## 📌 Project Overview
This website is a professional, responsive personal portfolio built for ISDS 4125 using a **hybrid layout** architecture designed for recruiters and industry evaluators. It highlights my academic background in Information Systems and Analytics at LSU, my corporate experience in automotive risk analytics and financial management, and an end-to-end enterprise capstone analytics project.

### Key Structure & Files
1. **`index.html` (Landing Page — Single-Page Architecture):**
   * **Profile / Hero:** Headline, status pill, core value proposition, key metric callouts, and professional photographic portrait.
   * **About / Background:** Overview of my studies in Information Systems and Analytics at LSU, core pillars, and bilingual capability (English & Mandarin Chinese).
   * **Skills & Competencies:** Categorized skill cards across BI/Data Visualization (PowerBI, Tableau), Technical Tools (Python, SQL, GitHub, Data Warehousing), Risk & Financial Operations (BOM, PO systems, procurement), and Coursework.
   * **Experience / Jobs Held:** Chronological timeline detailing roles as Auto Risk Analyst Intern at Assurant, Treasurer & Financial Analyst for Formula SAE TigerRacing ($60K+ budget, -23% costs), and Assistant Project Manager at Grabince Industrial LLC.
   * **Contact:** Direct channels (email, phone, LinkedIn) and interactive messaging form.
2. **`resume.html` (Dedicated Resume Page):**
   * Formal, printable digital resume expanding on education, professional work experience, technical competencies, and coursework.
   * Features `@media print` styling and a one-click **"Print / Save as PDF"** action button.
3. **`project.html` (Dedicated Project Showcase Page):**
   * Deep-dive case study on **SupplyPulse**, an enterprise predictive inventory and supply chain telemetry platform.
   * Details the bullwhip effect problem statement, 4-phase system architecture, ARIMA demand forecasting engine, interactive web telemetry, and business KPI results (-23% stockouts, +18% forecast precision).
4. **`styles.css` (Shared Design System):**
   * Unified modern dark-slate theme (`#070a12`, `#111827`) with vibrant indigo and electric teal accents (`#6366f1`, `#06b6d4`), glassmorphism, responsive navigation, and mobile-friendly layouts.

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
