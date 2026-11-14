# Neha Vishe — Neon Purple Portfolio

Responsive personal portfolio made with HTML5 and CSS3. No JavaScript framework or build tools are required.

## Files
- `index.html` — page content and sections
- `style.css` — theme, layout, responsive design and animations
- `profile-placeholder.svg` — temporary avatar shown until you add your photo
- `README.md` — this guide

## Add your profile photo
1. Copy a clear photo into this folder (beside `index.html`).
2. Rename it exactly `profile.jpg`.
3. Refresh the website. It will replace the placeholder automatically.
If your photo is PNG, change `profile.jpg` in the image tag in `index.html` to your exact filename.

## Personalize the content
Open `index.html` in VS Code. Use Ctrl+F to find and replace:
- `YOUR_EMAIL@example.com` with your email address.
- `https://www.linkedin.com/` with your LinkedIn profile URL.
- Sample project links with direct links to your project repositories.
Edit the About, skills, project and achievement text to keep it accurate. The skill bars are illustrative only; adjust their widths if you want.

## Preview locally
Open this folder in VS Code and open `index.html` with Live Server, or double-click `index.html` in File Explorer.

## Update your EXISTING GitHub repository
Repository: https://github.com/nehavishe123/portfolio-website

1. Open the repository and stay on the Code tab, branch `main`.
2. Choose **Add file → Upload files**.
3. Upload the individual files from this folder: `index.html`, `style.css`, `profile-placeholder.svg`, and `README.md`.
4. After adding your own photo, also upload `profile.jpg`.
5. Existing files with the same names will be replaced when you commit the changes.
6. Enter commit message: `Upgrade portfolio with neon purple design`.
7. Click **Commit changes**.

Do not create a new repository and do not upload only the ZIP file. GitHub Pages is already configured for `main` and `/(root)`, so it should publish automatically after the commit.

## Verify publication
1. Open the repository's Actions tab.
2. Wait for `pages build and deployment` to show a green check.
3. Visit https://nehavishe123.github.io/portfolio-website/
4. If the old design remains visible, press Ctrl + Shift + R to hard-refresh.

## Checklist
- [ ] Add `profile.jpg`
- [ ] Replace email placeholder
- [ ] Add your LinkedIn profile URL
- [ ] Replace sample project links
- [ ] Verify achievement details
- [ ] Preview desktop and mobile
- [ ] Upload updated files to existing repository
- [ ] Confirm green check in Actions
- [ ] Test the live site
