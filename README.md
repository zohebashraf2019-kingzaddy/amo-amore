# Amo Amore Aesthetics Website

Static HTML/CSS/JavaScript demo ready for GitHub + Vercel.

## Included
- Responsive luxury beauty design based on the supplied horizontal design reference
- Amo Amore logo and owner image
- Services organized by category with pricing, timing, and deposit notes
- Service bag / cart demo
- Current GlossGenius booking links
- Responsive grid gallery with full-screen lightbox and previous/next arrows
- About section, policies, Reno address and business hours
- Contact inquiry form UI

## Deploy to GitHub + Vercel
1. Upload the entire folder contents to a GitHub repository.
2. In Vercel, choose **Add New > Project** and import the repository.
3. Framework preset: **Other**.
4. Build command: leave blank.
5. Output directory: leave blank.
6. Deploy.

## Before production launch
- Add the owner's final biography.
- Add the owner's email and connect the contact form (Formspree, EmailJS, serverless function, etc.).
- Replace the GlossGenius booking URL when the custom booking/payment portal is ready.
- Confirm final pricing, service descriptions, deposits, policies, and business hours with the owner.
- If you later add direct checkout, use a secure payment provider such as Stripe and process deposits server-side rather than storing card data in this website.

## Main files
- `index.html`
- `styles.css`
- `script.js`
- `assets/`
