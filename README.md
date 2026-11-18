# Nourhan Mohamed Ibrahim Anwar | Cybersecurity Portfolio

A single-page, static portfolio website for a Junior SOC Analyst candidate. Built with plain HTML5, CSS3, and vanilla JavaScript. No frameworks, no build step, no backend, no external dependencies.

## Project structure

```
portfolio/
├── index.html     # Page content and structure
├── style.css      # Design system and responsive layout
├── script.js      # Mobile menu, active nav link, scroll reveal
├── netlify.toml   # Netlify publish settings and security headers
└── README.md      # This file
```

## Preview locally

Double-click `index.html` to open it in your browser. No server is needed.

## Deploy: GitHub + Netlify (about 10 minutes)

### Step 1: Upload to GitHub

1. Sign in at https://github.com and click **New repository**.
2. Name it (for example `portfolio`), keep it **Public** or **Private**, and click **Create repository**.
3. On the new repository page, click **uploading an existing file**.
4. Drag in **all files** from the project folder (`index.html`, `style.css`, `script.js`, `netlify.toml`, `README.md`). Upload the files themselves, not a folder that contains them, so `index.html` sits at the repository root.
5. Click **Commit changes**.

### Step 2: Connect to Netlify

1. Sign in at https://app.netlify.com (using your GitHub account is easiest).
2. Click **Add new site** > **Import an existing project**.
3. Choose **GitHub**, authorize Netlify if asked, and select your portfolio repository.
4. Leave **Build command** empty and set **Publish directory** to `.` (already set by `netlify.toml`).
5. Click **Deploy**.

### Step 3: Get your public HTTPS URL

1. When the deploy finishes (usually under a minute), Netlify shows a URL such as `https://random-name.netlify.app`.
2. Go to **Site configuration** > **Change site name** to pick a cleaner name, for example `nourhan-anwar.netlify.app`.
3. HTTPS is enabled automatically.

### Step 4: Make your QR code

1. Open your live URL on your phone and confirm everything loads.
2. Use any trusted QR code generator and paste your **final HTTPS URL** (the one from the Netlify site name you chose).
3. Download the QR code as **PNG or SVG** at high resolution.
4. Print a test copy at the real size on your ID card and scan it with two different phones before the final print. Keep a quiet margin around the code and use dark code on a light background.

> Tip: set your final site name **before** generating the QR code. If you change it later, the old URL stops working.

## Publishing checklist

- [ ] All files uploaded to the GitHub repository root
- [ ] Netlify deploy shows **Published**
- [ ] Site name chosen and final URL copied
- [ ] Opened the live URL on a phone: layout looks right
- [ ] **View My CV** opens the CV in a new tab
- [ ] **LinkedIn Profile** opens your LinkedIn in a new tab
- [ ] **View My Infographic** opens the infographic in a new tab
- [ ] Email link opens a draft to your address
- [ ] Google Drive files are set to **Anyone with the link can view** (open each link in a private window to confirm)
- [ ] QR code scanned successfully on at least two phones before printing

## Updating the site later

Edit a file on GitHub (pencil icon), commit, and Netlify redeploys automatically within a minute.

To change a link, search for it in `index.html`. The CV, infographic, and LinkedIn URLs appear in the hero section, and LinkedIn and email also appear in the contact section.

## Notes

- Colors are defined as CSS variables at the top of `style.css`.
- The site uses system fonts, so it loads fast and needs no external requests.
- Animations respect the user's reduced-motion setting.
