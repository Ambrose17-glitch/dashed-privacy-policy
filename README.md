# DASHED Privacy Policy — GitHub Pages package

This folder contains a simple, mobile-friendly public policy website for DASHED.

## Files
- `index.html` — Privacy Policy (intended public policy URL)
- `account-deletion.html` — public account/data deletion request instructions

## Publish on GitHub Pages
1. Sign in to GitHub.
2. Create a **public** repository named `dashed-privacy-policy`.
3. Upload `index.html` and `account-deletion.html` to the repository root (the top-level folder).
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then save.
7. Wait for deployment and open the published URL shown in Settings → Pages. It will normally look like:
   `https://YOUR-GITHUB-USERNAME.github.io/dashed-privacy-policy/`
8. The account deletion page will normally be:
   `https://YOUR-GITHUB-USERNAME.github.io/dashed-privacy-policy/account-deletion.html`

Do not submit a guessed URL to Google Play; first open both pages in a private/incognito browser window and confirm they load publicly over HTTPS.

## Before publishing / Google Play submission
This is a prepared draft based on the known DASHED project context. The app owner must verify that each statement matches the actual app and backend:
- which data the released app collects, including location and diagnostic information;
- the actual Supabase and Maps configuration and other SDKs/providers;
- how account deletion is implemented in the app and backend;
- the real process and timeframe for processing deletion requests;
- any retention obligations for order/payment records.

Google Play requires a public privacy policy and, for apps that support account creation, an in-app deletion path and a working web resource for requesting account deletion. Add the published URLs in the relevant Play Console fields and complete Data safety accurately. The email-based deletion process described here must be monitored and requests must actually be processed.

## Important
This package is not yet published to GitHub. It does not configure the user's GitHub account or automatically connect `dashed.site`. Keep the Admin Dashboard unpublished. Connect a custom domain only after deliberately choosing the correct DNS and GitHub Pages configuration.
