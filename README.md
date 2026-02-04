# NTUMEDSA Navigator

A premium, high-performance navigator for NTUMEDSA (國立臺灣大學醫學系學生會). This site serves as a central hub for all MEDSA-related services, including event signups, Notion resources, and student affairs.

## Features
- ✨ **Premium Design**: Modern aesthetic with glassmorphism and smooth animations.
- 📱 **Fully Responsive**: Optimized for mobile, tablet, and desktop.
- 🚀 **Netlify Ready**: Pre-configured for seamless deployment.
- 🔍 **SEO Optimized**: Built-in meta tags for social sharing and search engines.

## Included Links
- Event Signup Center
- MedNote (Notion)
- Media Center
- Quiz System
- Student Affairs & Feedback
- MedWiki Public Info

## Deployment to Netlify

### Option 1: Using Netlify CLI
1. Install Netlify CLI: `npm install netlify-cli -g`
2. Run `netlify deploy --prod` inside this folder.

### Option 2: Manual Upload
1. Drag and drop this folder onto the Netlify [Deploy](https://app.netlify.com/drop) page.

### Option 3: Git Integration (Recommended)
1. Push this repository to GitHub/GitLab.
2. Connect the repository to Netlify via the Netlify Dashboard.
3. Set the build command to `(None)` and publish directory to `.`.

## Domain Configuration (Important)
To avoid the apex domain (`ntumedsa.org`) redirect issues mentioned with Google Sites:
1. Go to your Netlify site settings > Domain management.
2. Add `ntumedsa.org`.
3. Set `ntumedsa.org` as the **Primary domain**. Netlify will automatically handle the `www` redirect correctly.
4. Update your DNS settings on your domain registrar to point to Netlify's DNS or CNAME/A records.

---
Created with ❤️ by Antigravity for NTU MEDSA.
