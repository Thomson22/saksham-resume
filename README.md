# Saksham Kataria — Personal Resume Website (IIMB BBA DBE Module 3)

This repository contains the multi-page semantic HTML5 personal resume website for **Saksham Kataria** (Roll No. `26121112`, Email: `saksham.kataria26@iimb.ac.in`, Address: `Punjabi Colony, Samastipur, Bihar - 848101`), created for the **Website Development (Module 3)** course at the **Indian Institute of Management Bangalore (IIMB)** instructed by **Prof. Govind Shenoy**.

## Repository Structure

- `index.html` — Home & Resume page (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<address>`, `<footer>`) covering Career Summary, Work Experience & Leadership, and Education History.
- `projects.html` — Dedicated Projects & Case Competitions page featuring `<article>` cards for DukaanSetu, CDPG Team LexToken, LoopRoute, Dunzo Turnaround Study, and the Module 3 Website Project.
- `skills.html` — Dedicated Skills & Certifications page using semantic `<table>`, `<thead>`, `<tbody>`, and `<progress>` elements.
- `contact.html` — Dedicated Hobbies & Extracurriculars (`<details>` and `<summary>`) plus Contact page.

*(Note: Every `.html` page includes a built-in base64 portrait avatar and an interactive "Upload / Change Photo" button so your photo works out-of-the-box without broken image paths, and all four `.html` files link seamlessly to each other when placed in the same folder.)*

## How to Open Locally or Deploy on GitHub Pages

1. **Important for Local Viewing**: Extract all files (`index.html`, `projects.html`, `skills.html`, `contact.html`) from the `.zip` archive into the **same folder** on your laptop before opening `index.html` in your browser so the multi-page navigation links (`href="projects.html"`, etc.) resolve properly.
2. **Deploy on GitHub Pages**:
   - Create a new **Public** repository on GitHub (e.g., `saksham-resume`).
   - Upload `index.html`, `projects.html`, `skills.html`, `contact.html`, and `README.md` to the root of the repository and click **Commit changes**.
   - Open **Settings → Pages**, select **Deploy from a branch**, choose branch **`main`** and folder **`/ (root)`**, and click **Save**.
