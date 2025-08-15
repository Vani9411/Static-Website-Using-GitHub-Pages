
🌐 Deploy Static Website to GitHub Pages — Full Project Guide

This guide explains how to create, upload, and deploy a static website to GitHub Pages for free.
We’ll cover everything from project setup to live hosting.


---

🛠 1. Prepare Your Static Website

Before deploying, you need your static site ready. A static website contains:

index.html → Main homepage file

style.css → Styling file (optional but recommended)

script.js → JavaScript functionality (optional)

assets/ → Images, fonts, icons, etc.

Example folder structure:

my-static-site/
│
├── index.html
├── style.css
├── script.js
└── assets/


---

🖥 2. Install Required Tools

You’ll need:

1. Git → Download & Install


2. GitHub Account → Sign Up Here


3. Your static website files ready



To verify Git installation:

git --version


---

📦 3. Create a New GitHub Repository

1. Go to GitHub and log in


2. Click New Repository (➕ button)


3. Name it (e.g., my-static-site)


4. Keep Visibility: Public


5. Do not add a README file yet


6. Click Create Repository




---

📤 4. Upload Your Website Files via Git

Step 4.1 — Clone the Empty Repository

git clone https://github.com/<your-username>/<repo-name>.git

Step 4.2 — Add Your Website Files

Copy your index.html, style.css, script.js, and assets/ into the cloned repository folder.

Step 4.3 — Stage & Commit Files

cd <repo-name>
git add .
git commit -m "Initial commit - Add static site"

Step 4.4 — Push to GitHub

git push origin main


---

🚀 5. Enable GitHub Pages

1. Open your repository in GitHub


2. Go to Settings → Pages


3. Under Source, select:



Branch: main

Folder: / (root)

4. Click Save


5. Wait for GitHub Pages to build your site




---

🔗 6. Access Your Live Website

GitHub will provide you a URL like:

https://<your-username>.github.io/<repo-name>/

Visit it in your browser — your static site is now live! 🎉


---

🔄 7. Update Your Site Anytime

Whenever you change files:

git add .
git commit -m "Update site content"
git push origin main

GitHub Pages will automatically redeploy with the new changes.


---




This project can be used freely for personal and commercial purposes.

--- give me I'm created
