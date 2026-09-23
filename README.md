# Nikunj Chaudhary – Personal Academic Website

An ultra-clean, minimalist personal academic website inspired by [nat.org](https://nat.org/), customized for a PhD Candidate in Economics at the Indian Institute of Management (IIM) Lucknow.

## Features
- **nat.org aesthetic**: Fast, typography-focused, distraction-free, zero bloated frameworks (< 15 KB).
- **Responsive & Dark-Mode Ready**: Automatically switches theme based on system preference (`prefers-color-scheme`).
- **Academic Sections**:
  - Bio & Research Fields (Applied Microeconomics, Development Economics, Econometrics)
  - Working Papers with interactive collapsible abstract previews (`<details>` without JavaScript)
  - Work in Progress
  - Teaching Experience (IIM Lucknow courses)
  - *"Some things I believe"* philosophical/methodological tenets in Economics & Research
  - Education & Academic Background
  - Code & Replication Links
  - Contact details & Office location
- **GitHub Pages Ready**: Includes an automated deployment workflow `.github/workflows/deploy.yml`.

---

## Quick Setup & Customization

1. **Edit Content**:
   Open `index.html` in any text editor and update:
   - Your email address
   - Paper titles, abstracts, and draft PDF links
   - Social & profile links (Google Scholar, SSRN, LinkedIn, X/Twitter)
   - Add your CV as `cv.pdf` in the root folder so the `[CV (PDF)]` link opens it directly.

2. **Preview Locally**:
   Run a simple local server in your terminal:
   ```bash
   python3 -m http.server 8000
   ```
   Then open `http://localhost:8000` in your web browser.

---

## Hosting on GitHub Pages

### Option 1: As your primary user site (Recommended)
1. On GitHub, create a new repository named:
   ```
   Nikunj199805.github.io
   ```
   *(Make it Public)*
2. In your terminal, run:
   ```bash
   git remote add origin git@github.com:Nikunj199805/Nikunj199805.github.io.git
   git branch -M main
   git push -u origin main
   ```
3. In GitHub repo **Settings &rarr; Pages**, under **Build and deployment**, select **GitHub Actions** (or Deploy from branch `main` / root).
4. Your website will be live at:
   ```
   https://Nikunj199805.github.io/
   ```

### Option 2: As a project site (e.g., repository named `website`)
1. Create a repository named `website` on GitHub.
2. In your terminal, run:
   ```bash
   git remote add origin git@github.com:Nikunj199805/website.git
   git branch -M main
   git push -u origin main
   ```
3. Your website will be live at:
   ```
   https://Nikunj199805.github.io/website/
   ```
