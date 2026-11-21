# AI calc Privacy Policy

Static website for the privacy policy of **AI calc** by Ajirix Technologies.
No build step: plain HTML, ready for GitHub Pages.

## Files

| File | Purpose |
|---|---|
| `index.html` | The privacy policy page |
| `assets/` | App icon, Ajirix logo and favicons |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publish on GitHub Pages

1. Create a new **public** repository on GitHub, for example `aicalc-privacy-policy`.
2. Upload these files to it (keep the `assets` folder), or push them with Git:
   ```powershell
   cd path\to\aicalc-privacy-policy
   git init
   git add .
   git commit -m "AI calc privacy policy"
   git branch -M main
   git remote add origin https://github.com/<your-username>/aicalc-privacy-policy.git
   git push -u origin main
   ```
3. On GitHub, open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, pick the **main** branch and the **/ (root)** folder, then **Save**.
5. After a minute or two, the site is live at:
   `https://<your-username>.github.io/aicalc-privacy-policy/`

Use that address as the **Privacy Policy URL** on APKPure and Google Play.

## Updating the policy

Edit `index.html`, change the **Effective** date near the top, then commit and push. GitHub Pages republishes automatically.
