# Beard Industries (Static Site)

Static marketing site for Beard Industries LLC. This repo is plain HTML/CSS with image assets and no build tooling.

**What’s Here**
- `index.html`: Home page.
- `contact/`: Contact page.
- `terms/`: Terms of use page.
- `privacy/`: Privacy policy page.
- `css/`: Stylesheets.
- `assets/images/`: Image assets.

**Local Preview**
1. `cd */beardindustries`
2. `python3 -m http.server 8000`
3. Open `http://localhost:8000`

**Deployment Notes (AWS Amplify)**
- No build step required.
- Output directory is the site root: `.`
- Any static host (Amplify Hosting, S3 + CloudFront, Netlify, etc.) will work.

**Known Issues**
- None currently noted.
