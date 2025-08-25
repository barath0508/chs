# Web Deployment Instructions

## Option 1: GitHub Pages (Recommended - Free)

1. **Create GitHub Repository:**
   - Go to https://github.com and create a new repository
   - Name it something like `siva-birthday-page`
   - Make it public

2. **Upload Files:**
   - Upload `index.html` and `README.md` to your repository
   - Or use Git commands:
     ```bash
     git init
     git add .
     git commit -m "Add birthday page"
     git branch -M main
     git remote add origin https://github.com/YOUR_USERNAME/siva-birthday-page.git
     git push -u origin main
     ```

3. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click Save

4. **Access Your Site:**
   - Your site will be available at: `https://YOUR_USERNAME.github.io/siva-birthday-page`
   - It may take a few minutes to deploy

## Option 2: Netlify (Free)

1. Go to https://netlify.com
2. Drag and drop your HTML folder to deploy instantly
3. Get a free URL like `https://random-name.netlify.app`

## Option 3: Vercel (Free)

1. Go to https://vercel.com
2. Import your GitHub repository or upload files
3. Get instant deployment with custom domain options

## Quick Deploy with Netlify Drop:
1. Visit https://app.netlify.com/drop
2. Drag your HTML folder containing `index.html`
3. Get instant live URL!