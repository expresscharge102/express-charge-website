# Express Charge SRL — Vercel Website

Static bilingual website (English / Romanian), ready for GitHub and Vercel.

## Files
- `index.html`
- `styles.css`
- `script.js`
- `vercel.json`

## Publish with GitHub + Vercel
1. Create a new GitHub repository, for example `express-charge-website`.
2. Upload all files from this folder to the repository root.
3. In Vercel, choose **Add New → Project**.
4. Import the GitHub repository.
5. Framework preset: **Other**.
6. Build command: leave empty.
7. Output directory: leave empty.
8. Deploy.

## Connect expresscharge.ro from Hostico
In Vercel:
1. Open the project.
2. Go to **Settings → Domains**.
3. Add:
   - `expresscharge.ro`
   - `www.expresscharge.ro`
4. Vercel will show the exact DNS records required.

In Hostico DNS management:
- Add the exact records displayed by Vercel.
- Usually Vercel requests:
  - an A record for the root domain;
  - a CNAME record for `www`.
Do not copy generic values from guides; use the values shown in your Vercel project.

## Quote form
The quote form opens the visitor's email application and prepares a message to:
`transport@expresscharge.ro`

No form data is stored on the website.

## Important contact data
- Phone / WhatsApp: +40 735 977 252
- transport@expresscharge.ro
- office@expresscharge.ro
- dispatch@expresscharge.ro
