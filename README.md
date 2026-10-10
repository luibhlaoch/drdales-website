# Dr Dale's website — GitHub Pages

This is a responsive, single-page homepage for Dr Dale's, styled around the existing cowboy / Wild West branding.

## Files
- `index.html` — page content and mobile navigation
- `styles.css` — colours, layout, typography and responsive styling
- `assets/dr-dales-branding.jpg` — your supplied cowboy brand illustration
- `assets/dr-dales-products.png` — your supplied product photograph

## Upload to GitHub from the Android app
1. Open GitHub and create a repository named `drdales-website` (or choose your existing website repository).
2. Open the repository, tap **Add file** if shown, then choose **Create new file** or upload files from your device.
3. Upload `index.html` and `styles.css` into the **top level** of the repository, and upload the whole `assets` folder with both images inside it. Keep the folder structure exactly as supplied.
4. Commit the changes.
5. In the repository, open **Settings → Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
7. Once GitHub Pages has published the site, connect `www.drdales.co.uk` under **Settings → Pages → Custom domain**.
8. At your domain provider, configure the DNS records GitHub Pages specifies. DNS changes can take time to propagate.

## Before publishing
- In `index.html`, replace the Facebook link `https://www.facebook.com/` with the official Dr Dale's page URL.
- Check the product descriptions and ensure they accurately reflect your actual recipes, ingredients and labels.
- Add your preferred contact details and any allergen / product information you want customers to see.
- If you already have a repository with a website, back up the existing files before replacing anything.

## Important
This is a static homepage. It does not process payments, accept orders, collect customer data, or provide a checkout. Those features would need a separate service or backend.
