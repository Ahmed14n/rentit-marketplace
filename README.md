# RentIt demo marketplace

RentIt is a responsive English-language rental marketplace demo with a branded splash screen, 54 sample listings across 9 categories, search, sorting and filters, saved items, item detail and booking request flows, renter/owner entry points, and owner/admin dashboard previews.

The visual identity follows the supplied RentIt reference: a turquoise and deep teal palette, an R mark with rental-item details, and the tagline “Rent What You Need, Rent Out What You Own!” on the opening splash screen. The rental cart supports multiple items, date and duration edits, a fee estimate, a checkout preview, and a locally saved demo order.

## Run it

1. Open `index.html` in a modern browser, or serve this folder with any static web server.
2. For example, from this folder run `python -m http.server 8000` and visit `http://localhost:8000`.

No build step or package installation is needed. Product photography loads from Unsplash, and Google Fonts load over the internet; browser access to those services improves the visual result. The rest of the site is plain HTML, CSS, and JavaScript.

## Publish a public link with GitHub Pages

1. Create a **public** GitHub repository named `rentit-marketplace`.
2. Upload the contents of this folder to the repository root (the `index.html` file must be at the root), then commit them to the `main` branch.
3. In the repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
4. GitHub will show the public site address in the Pages settings. It normally follows `https://YOUR-USERNAME.github.io/rentit-marketplace/`.

GitHub Pages serves this static demo publicly. The site uses no server-side code; creating a public website does not activate real accounts, bookings, or payments.

## Demo behavior and backend needs

Search, category selection, price and condition filters, sorting, saved items (local browser storage), item details, cart, and demo checkout work in the browser. The checkout does not accept card details or charge money. Booking confirmation with owners, account access, profiles, messages, publishing listings, real payment processing, payouts, identity checks, admin moderation, and persistent order data need a secure backend and a payment provider before real use.

All listing content is illustrative sample data. No real rental availability, owners, or transactions are represented.
