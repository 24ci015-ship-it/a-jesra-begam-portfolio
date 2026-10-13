# Responsive Personal Portfolio Website

This project is a complete, responsive personal portfolio website based on the tutorial by GreatStack.

## Project Structure
```
portfolio_website/
│
├── index.html          # Main HTML structure
├── style.css           # CSS Styling & Responsive Design
├── script.js           # Interactive tabs, mobile navigation & form script
└── images/             # Placeholder image assets
    ├── user.png
    ├── work-1.png
    ├── work-2.png
    └── work-3.png
```

## Features
- **Responsive Layout:** Adapts smoothly across mobile, tablet, and desktop screens.
- **Dynamic Tab Switching:** Toggle between Skills, Experience, and Education in the About section.
- **Mobile Drawer Menu:** Slide-out navigation drawer for mobile screens.
- **Google Sheets Form Integration:** Send contact form responses directly to a Google Sheet using Google Apps Script.

## Setting up Google Sheets Contact Form
1. Create a new Google Sheet.
2. Click `Extensions` -> `Apps Script`.
3. Paste the Google Apps Script code to catch `POST` data and append to rows.
4. Deploy as a Web App (`Execute as: Me`, `Who has access: Anyone`).
5. Copy the deployment URL and paste it into `script.js` under `scriptURL`.
