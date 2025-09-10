Facebook Landing — Netlify Deployment
Add this badge to your README so you can deploy with a single click:
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/your-username/facebook-landing)
Quick Start
1.	Install: npm i
2.	Run locally: npm run dev and visit the URL shown (usually http://localhost:5173).
3.	Build: npm run build
4.	Deploy to Netlify:
o	Push this folder to a new GitHub repo, then in Netlify click the Deploy to Netlify button above or use Add new site → Import from Git.
o	Or drag the generated dist/ folder into Netlify Sites → Deploys.
o	Build command: npm run build | Publish directory: dist
Netlify Forms
•	We include a hidden form in index.html so Netlify detects the form at build time.
•	After first deploy, go to Netlify → Forms → contact to confirm detections and set email notifications.
UTM Tracking
•	CTA already uses utm_source=facebook&utm_medium=cpc&utm_campaign=insurance&utm_content=landingpage.
Troubleshooting
•	If you previously saw Failed to parse configuration or ENAMETOOLONG, start with this minimal netlify.toml and redeploy.
•	If Forms aren’t detected, visit your Site settings → Forms → enable, then redeploy.
________________________________________
2.1) README with one‑click Deploy Button
README.md
# Facebook Landing — Netlify Deployment

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=REPLACE_WITH_YOUR_GITHUB_REPO_URL)

> **How to use the button:**
> 1. Create a GitHub repo with the exact files in this folder.
> 2. Replace `REPLACE_WITH_YOUR_GITHUB_REPO_URL` in the badge link above with your repo URL (e.g., `https://github.com/ShahwaliHotaki/facebook-landing`).
> 3. Click the button to spin up the site on Netlify—build settings are preconfigured.

## Quick Start (local)
1. **Install**: `npm i`
2. **Run locally**: `npm run dev` and visit the URL shown (usually `http://localhost:5173`).
3. **Build**: `npm run build`

## Deploy to Netlify (manual options)
- **Import from Git:** In Netlify click **Add new site → Import from Git**, select your repo, and keep:
  - Build command: `npm run build`
  - Publish directory: `dist`
- **Drag-and-drop:** Build locally (`npm run build`) and drag the `dist/` folder into **Sites → Deploys** in Netlify.

## Netlify Forms
- A hidden form in `index.html` ensures Netlify detects the form at build time.
- After first deploy, go to **Netlify → Forms → contact** to confirm detection and enable email notifications to `shahwali.hotaki@ikhlasinsurance.com`.

## UTM Tracking
- CTA already uses `utm_source=facebook&utm_medium=cpc&utm_campaign=insurance&utm_content=landingpage`.

## Troubleshooting
- If you previously saw `Failed to parse configuration` or `ENAMETOOLONG`, this minimal `netlify.toml` plus the provided structure fixes it.
- If Forms aren’t detected, visit your Site settings → Forms → enable, then redeploy.
