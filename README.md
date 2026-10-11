# Siwat Teimtad — Economist Portfolio Website

An academic portfolio website built for **Siwat Teimtad**, Economist and Researcher. Built for seamless zero-dependency deployment on **GitHub Pages**.

> *"Master Economics, the Simple Way."*

---

## 🚀 Live Site Preview & GitHub Pages URL
Once deployed to GitHub Pages, the site will be accessible at:
```
https://<your-github-username>.github.io/<your-repository-name>/
```

---

## 📁 Repository Structure

```
my_data/
├── index.html                 # Main landing page (Hero, About Me, Project Cards, Contact)
├── hazlitt-economics.html     # Academic paper on Hazlitt's Economics in One Lesson (1,800+ words)
├── game-theory.html           # Academic treatise on Game Theory & Economic Equilibria (1,800+ words)
├── style.css                  # Unified dark mode theme with JetBrains Mono typography
├── script.js                   # Client-side interactivity (Reading progress, copy email, smooth scroll)
├── black.png                  # Brand logo
├── plan/
│   └── our_plan.md            # Architectural and implementation plan
└── README.md                  # Project documentation & deployment guide
```

---

## ✨ Features & Specifications

- **Theme & Typography:**
  - Modern dark theme (`#0d1117`, `#161b22`, `#30363d`).
  - Google Font: `JetBrains Mono`.
  - Brand logo: `black.png`.
- **Hero Section:**
  - Centered quote: *"Master Economics, the Simple Way."*
  - Subtitle introducing Siwat Teimtad as an Economist & Researcher.
- **About Me & Contact:**
  - Name: **Siwat Teimtad**
  - Email: **`dx@outlook.com`**
  - Interactive one-click "Copy Email" button with instant toast notification + direct `mailto:` link.
- **Two Complete Academic Research Papers (1,800+ words each):**
  1. **Key Economic Concepts of *Economics in One Lesson* (Henry Hazlitt, 1946):**
     - The Axiom of the One Lesson (seen vs. unseen)
     - The Broken Window Fallacy
     - Public works & the illusion of state spending
     - Technological unemployment & machinery
     - Tariffs, protectionism, price controls, rent ceilings, and minimum wages
     - Inflation as a regressive tax (Cantillon Effect) & capital accumulation
  2. **Game Theory: Foundations, Strategic Equilibria & Economic Applications:**
     - Normal & Extensive form games
     - Payoff matrix, dominant strategies & the Prisoner's Dilemma
     - Nash Equilibrium (pure vs. mixed strategies)
     - Repeated supergames, Tit-for-Tat & the Folk Theorem
     - Information asymmetry, Akerlof's lemons & Spence's signaling
     - Mechanism design, Vickrey auctions & macroeconomic central bank credibility
- **Interactive Reading Features:**
  - Top scroll reading progress bar on article pages.
  - Sticky table of contents with smooth jump links.
  - Fully responsive on mobile, tablet, and desktop devices.

---

## 🚢 How to Deploy on GitHub Pages

### Method 1: Web Browser Upload (Fastest — No Git Install Required)

1. Go to [GitHub](https://github.com) and click **New repository**.
2. Set repository name (e.g. `siwat-portfolio` or `economist-portfolio`).
3. Set visibility to **Public** and check **Add a README file**.
4. Click **Create repository**.
5. Inside the new repo, click **Add file** &rarr; **Upload files**.
6. Drag and drop all files from this folder (`index.html`, `hazlitt-economics.html`, `game-theory.html`, `style.css`, `script.js`, `black.png`).
7. Click **Commit changes**.
8. Go to **Settings** &rarr; **Pages** (under "Code and automation" in the left sidebar).
9. Under **Build and deployment**:
   - **Source:** Select `Deploy from a branch`.
   - **Branch:** Select `main` and folder `/(root)`.
   - Click **Save**.
10. Wait 1–2 minutes, refresh the page, and your site is live!

---

### Method 2: Git Command Line

If you have Git installed on your computer:

```powershell
# In this directory:
git init
git add .
git commit -m "Initial portfolio commit for Siwat Teimtad"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main
```
Then enable GitHub Pages under repository Settings &rarr; Pages &rarr; Branch: `main` &rarr; Save.
