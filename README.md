# University-Guide
A centralized web application designed to streamline the university application process for international students.

# 🌍 International University Guide

An elegant, minimal, and fully client-side web portal designed specifically to help international students (with a focus on South African matric/NSC applicants) navigate the process of applying to universities abroad. 

The application streamlines research by aggregating system portals, documentation requirements, admission deadlines, acceptance rates, and scholarship insights for **13 countries**, along with an expanded view of the world's **Top 100 universities**.

---

## 🚀 Live Features

* **⚡ Splash & Welcome Screen:** A smooth introduction featuring high-level statistics (countries covered, top university counts) and a user-friendly entry trigger.
* **🗺️ Interactive Country Guides:** Comprehensive breakdowns of admissions setups for 13 destinations including the UK (UCAS), USA (Common App/Coalition), Germany (uni-assist), Switzerland, Singapore, Japan, and more.
    * *Portals & Direct Links:* Quick navigation links directly to official application portals.
    * *Requirements Checklist:* Specific requirement breakdowns—such as NSC/Matric results, SAT/ACT expectations, or country-specific maths exams (e.g., OMPT/Boswell-Bèta for the Netherlands).
    * *Key Notes & Context:* Hidden nuances, such as Oxford/Cambridge application restrictions, MEXT or GKS scholarship details, and tuition fee realities (e.g., free fees in Germany).
* **🏆 Global Top 100 Explorer:** A filterable database tracking the world's elite universities across 26 nations. Users can dynamically filter by country tabs or search globally using instant text matching.
* **📋 Interactive Document Checklist:** A dynamic workspace where applicants can track their gathered documents (e.g., certified copies, letters of recommendation, portfolios). It updates structural progress in real-time via an automated completion bar.
* **🌓 Native Dark Mode Support:** Respects the user's operating system preferences via native CSS Media Queries (`prefers-color-scheme`).

---

## 🛠️ Architecture & Tech Stack

This project is intentionally built as a lightweight, lightning-fast **Single Page Application (SPA)** with zero dependencies, external build tools, or heavy runtime libraries. 

* **Frontend Structure:** Semantic HTML5
* **Styling & UI:** Clean, modern CSS3 variables for color thematic controls, Flexbox/Grid systems, structural responsive layout design, and fluid transitions.
* **Icons:** [Tabler Icons Webfont](https://tabler.io/icons) via CDN.
* **Interactions & Data Handling:** Vanilla JavaScript (ES6+). All application states, country lists, and university objects are safely handled in-memory using highly optimized array filtering and DOM manipulation procedures.

---

## 📂 Project Structure

```text
├── BETTERSTYLE.html     # Single-file production-ready application (HTML, CSS, JS)
└── README.md            # Repository documentation
