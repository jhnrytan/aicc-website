# Publish the AICC website with GitHub Pages

## Before publishing
1. Open `terms.html` and `privacy.html`.
2. Replace every bracketed placeholder:
   - `[INSERT YOUR FULL NAME OR LEGAL BUSINESS NAME]`
   - `[INSERT A MONITORED CONTACT EMAIL]`
   - `[INSERT THE JURISDICTION THAT ACTUALLY APPLIES TO YOU]`
3. Make sure the Privacy Policy accurately reflects the exact AICC build and integrations you use.
4. Do not publish the pages with placeholders or inaccurate statements. This template is not legal advice.

## Create the GitHub repository
1. Sign in at https://github.com/.
2. Create a **public** repository named `aicc-website` (or another name you prefer).
3. Upload the contents of this folder to the repository root. The root should contain `index.html`, `terms.html`, `privacy.html`, and the `assets` folder.
4. Commit the files to the `main` branch.

## Enable GitHub Pages
1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then click **Save**.
4. Wait for GitHub Pages to finish deployment.
5. Open the published homepage shown in the Pages settings.

Your URLs should look like:

- Homepage: `https://YOUR-GITHUB-USERNAME.github.io/aicc-website/`
- Terms: `https://YOUR-GITHUB-USERNAME.github.io/aicc-website/terms.html`
- Privacy: `https://YOUR-GITHUB-USERNAME.github.io/aicc-website/privacy.html`

Replace `YOUR-GITHUB-USERNAME` with your real GitHub username. Do not submit example URLs.

## Verify the pages
Open both policy links in a private/incognito browser window. Confirm:
- The URL starts with `https://`.
- The page loads without signing in.
- It displays the full policy text.
- The homepage links to both policies.
- No placeholder text remains.

## TikTok Developer Portal
Use the exact public URLs for Terms of Service and Privacy Policy in your app details. If TikTok separately asks you to verify URL properties or domain ownership, follow the verification method shown in the TikTok portal. GitHub Pages hosting does not automatically complete TikTok's separate property verification.
