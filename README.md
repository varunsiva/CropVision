# CropVision — Project Website & Documentation Portal (Activity 4)

This portal was developed to satisfy **Activity 4 — Project Website / Documentation Portal** of the **Technical Enrichment Activities (35 Marks)** for the Final Year Engineering Project.

---

## 📁 Directory Structure

The website is kept completely isolated from the mobile application and backend code:

```
final year projct/
├── website/                   # Dedicated documentation portal
│   ├── index.html             # Main portal page
│   ├── styles.css             # Agricultural tech CSS theme
│   ├── app.js                 # Interactive pipeline simulator & tabs
│   ├── assets/                # Media assets (placeholders for demo.mp4, etc.)
│   └── README.md              # Portal documentation (this file)
├── mobile_app/                # Flutter mobile application (untouched)
├── model/                     # Python & PyTorch ML pipeline (untouched)
└── backend/                   # Supabase database & SQL schemas (untouched)
```

---

## 🚀 How to Run the Website Locally

You can run this website on any system using Python's built-in HTTP server or directly in any web browser.

### Option 1: Python HTTP Server (Recommended)
Open PowerShell or your terminal in the `website` directory:
```powershell
# Navigate to the website folder
cd "c:\Users\Varun\Desktop\final year projct\website"

# Start the local server on port 3000
python -m http.server 3000
```
Open your browser and visit: **`http://localhost:3000`**

### Option 2: Direct File Open
You can also double-click `website/index.html` or open it directly in Google Chrome, Microsoft Edge, or any modern browser.

---

## 🌐 How to Deploy Online for Free

For project submission and evaluation by your project guide or university panel:

### Method A: GitHub Pages (Easiest)
1. Push your repository to GitHub.
2. In your repository on GitHub, go to **Settings** → **Pages**.
3. Under **Build and deployment** → **Source**, select `Deploy from a branch`.
4. Choose the `main` branch and specify the `/website` folder (or copy `index.html`, `styles.css`, and `app.js` into a `docs` folder or `gh-pages` branch).
5. Click **Save**. GitHub will provide a live URL (e.g. `https://cropvision-team.github.io/CropVision/`).

### Method B: Vercel / Netlify
1. Drag and drop the `website` directory directly into [Netlify Drop](https://app.netlify.com/drop) or import into [Vercel](https://vercel.com).
2. It will deploy instantly with a live, shareable public URL with free SSL.

---

## 📋 Information You Can Personalize Before Final Submission

1. **Team Details (`website/index.html` under `#team`)**:
   - Team Members configured: **Varun**, **Deepan**, **Ripen**, and **Udhay**.
   - Faculty Guide: **Project Guide / Mentor**.
2. **Demonstration Video (`website/index.html` under `#video-demo`)**:
   - Record a 2–4 minute walkthrough of your app in action.
   - Save the file as `website/assets/demo.mp4` or embed your uploaded YouTube/OneDrive link.
3. **Screenshots (`website/index.html` under `#showcase`)**:
   - Take actual device screenshots from your phone or Android emulator and replace the illustrative CSS mockups with your exported JPG/PNG images if preferred.

---

## ✅ Activity 4 Compliance Matrix

| Requirement from Rubric | Implementation on this Portal |
| :--- | :--- |
| **Project Objectives** | Stated in dedicated `#objectives` section: validation gate, MobileViT, severity estimation, treatment engine. |
| **Problem Statement** | Documented in `#problem` section: farmer challenges, detection delays, and necessity of stage-based treatments. |
| **Methodology & Architecture** | Visualized in `#methodology` section with flowchart, formula, and G0–G3 threshold matrix. |
| **Team Details** | Provided in `#team` section with student slots, USN fields, and faculty guide designation. |
| **Project Progress** | Mapped in `#progress` section across the 6 development phases verified from the codebase. |
| **Documentation** | Interactive tabs in `#docs` detailing prerequisites, Supabase backend, ML server, and Flutter setup. |
| **GitHub Repository Link** | Integrated in header navigation, hero action buttons, and footer (`https://github.com/CropVision-Team/CropVision.git`). |
| **Demonstration Video** | Dedicated responsive player slot in `#video-demo` with guidance on attaching recorded walkthroughs. |
