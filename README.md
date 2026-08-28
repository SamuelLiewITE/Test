# ITE College West - Best Student Nomination Portal

An interactive, responsive single-page web application designed for **ITE College West** (Singapore) faculty, lecturers, and advisors to submit, evaluate, and manage student award nominations.

---

## 🌟 Features

- **5-Step Nomination Wizard**:
  1. **Nominator Particulars**: Staff ID, School/Department, Designation, and contact details.
  2. **Nominee Profile & Academics**: Legal student name, Matriculation ID (`240XXXXX`), dynamic course selector by school, cGPA (0.00–4.00), and attendance rate (%).
  3. **Award Category & Holistic Merits**: Supports authentic ITE awards (*Lee Kuan Yew Model Student Award, Technical Excellence, Leadership & Service, Innovation & Enterprise, and Resilience Spirit*), CCA records, leadership tiers, and VIA volunteering hours.
  4. **Qualitative Testimonials & Character**: Concrete justifications, character strength tags, portfolio links, and certificate upload simulation.
  5. **Review & Official Sign-off**: Detailed dossier verification with official declaration acknowledgment.

- **Real-Time Holistic Score Gauge**:
  - Automatically calculates an aggregate holistic score (0–100) across Academics, CCA Grade, Leadership/Community VIA, and Competition Distinctions.
  - Dynamic achievement tier indicator (*Outstanding Distinction, High Distinction, Commended Merit*).

- **Nomination Review Dashboard**:
  - Search by student name, ID, or nominator.
  - Filter by School (`SEIT`, `SBS`, `ENGG`, `SOH`), Award Category, or Review Status (`Pending Review`, `Shortlisted`, `Endorsed`).
  - View full printable dossier modal formatted for print and PDF export (`@media print`).
  - Export data to **CSV** (spreadsheet-ready) and **JSON**.
  - Local persistence via `localStorage` with sample data reload option.

- **Zero-Dependency Architecture**:
  - Standalone `index.html` file containing HTML, CSS, and vanilla JavaScript.
  - No node, npm, backend, or server installations required.

---

## 🚀 Getting Started

Simply open `index.html` in any modern web browser (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari).

### Enable Free GitHub Pages Live Hosting
1. Go to your repository's **Settings** > **Pages**.
2. Under **Build and deployment** > **Branch**, select `main` (or `master`) and folder `/ (root)`.
3. Click **Save**. Your site will be published at `https://<your-username>.github.io/<repo-name>/`.

---

## 🏫 Participating Schools
- **SEIT**: School of Electronics & Info-Comm Technology
- **SBS**: School of Business & Services
- **ENGG**: School of Engineering
- **SOH**: School of Hospitality
