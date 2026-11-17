# dharwad.online — GitHub Pages starter

A responsive static multi-page marketplace frontend for Dharwad.

## Included pages
- `index.html` — homepage
- `businesses.html`, `properties.html`, `vehicles.html`, `products.html`, `labour.html`, `services.html` — category pages
- `post-listing.html` — demo listing form
- `listing.html` — listing detail page
- `about.html` — about and indicative pricing
- `contact.html` — contact information placeholder

## Deploy to GitHub Pages
1. Create a **public** GitHub repository named `dharwad-online` (GitHub Free requires a public repository for Pages).
2. Upload all files and folders from this project. Keep `index.html` at the repository root.
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Choose branch `main`, folder `/ (root)`, then Save.
6. Wait for the published `github.io` URL shown in Settings → Pages.

## Keep Google Sites live
Do not change your domain nameservers or existing apex (`@`) and `www` DNS records. First test the GitHub Pages URL. Later, a staging subdomain such as `staging.dharwad.online` can be connected by adding only the exact DNS record GitHub Pages instructs you to add at the current DNS provider. Confirm who controls DNS before editing records.

## Important limitations — this is frontend only
GitHub Pages serves static files. This starter does **not** include:
- Shared online listing database or user accounts
- Secure admin login or moderation
- Real image uploads
- PhonePe payment processing
- Subscription activation, renewal or expiry
- Server-side validation or private API keys

The post-listing form stores data in the visitor's browser `localStorage` for demonstration only. It does not submit listings to a central website database. Do not put secret keys or database service-role keys in frontend JavaScript. For production, add a secure backend and database/storage service (for example, an API hosted separately and Supabase with correctly configured public access policies).

## Before public launch
- Replace sample listings with verified advertiser-approved content.
- Add official contact details and privacy/terms pages.
- Configure backend, image storage, admin moderation, spam protection and payment integration.
- Test mobile layout, accessibility and all links.
