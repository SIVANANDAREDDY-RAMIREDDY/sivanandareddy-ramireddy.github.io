# Siva Nanda Reddy Ramireddy – Portfolio

Professional personal portfolio website for an aspiring Electrical & Electronics Engineer specializing in Embedded Systems, IoT, and Control Systems.

**Live Demo:** After enabling GitHub Pages, your site will be available at:  
`https://<your-username>.github.io/<repo-name>/`

---

## Features

- Clean, modern dark theme
- Fully responsive (mobile, tablet, desktop)
- Smooth scroll navigation
- Mobile hamburger menu
- Sections: About, Education, Skills, Projects, Experience, Achievements, Contact
- Lightweight – pure HTML, CSS & JavaScript (no frameworks)

---

## How to Deploy on GitHub Pages

### 1. Create a new repository
1. Go to [GitHub](https://github.com) → **New repository**
2. Name it (e.g. `portfolio` or `siva-nanda-reddy`)
3. Keep it **Public**
4. Do **not** initialize with README (we already have one)

### 2. Upload these files
Upload the following files to the root of your repository:
- `index.html`
- `styles.css`
- `script.js`
- `README.md` (optional)

You can drag & drop them in the GitHub web interface, or use Git:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
cd YOUR-REPO
# copy the files here
git add .
git commit -m "Initial portfolio"
git push origin main
```

### 3. Enable GitHub Pages
1. Go to your repository → **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Choose branch: `main` (or `master`)
4. Folder: `/ (root)`
5. Click **Save**

Your site will be live in 1–2 minutes at:  
`https://YOUR-USERNAME.github.io/YOUR-REPO/`

---

## Customize Before Uploading

Open `index.html` and replace these placeholders:

1. **Profile Photo**  
   - Add your photo as `profile.jpg` in the same folder as `index.html`  
   - Recommended: square image, at least 400×400 px  
   - Until you add it, a professional “SNR” initials avatar is shown automatically

2. **GitHub**  
   - Replace every `YOUR-GITHUB-USERNAME` with your real GitHub username  
   - Update project repo links:
     - `smart-water-pump-controller`
     - `foot-step-power-generator`  
     (or change them to match your actual repo names)

3. **Email & LinkedIn**  
   - `your.email@example.com` → your real email  
   - `https://linkedin.com/in/your-profile` → your LinkedIn URL

---

## Local Preview

Just open `index.html` in any modern browser, or use a simple local server:

```bash
# Python
python -m http.server 8000

# Node (if you have it)
npx serve .
```

Then visit `http://localhost:8000`

---

## Tech Stack

- HTML5
- CSS3 (Custom Properties, Flexbox, Grid)
- Vanilla JavaScript

---

**Made for GitHub Pages · 2026**
