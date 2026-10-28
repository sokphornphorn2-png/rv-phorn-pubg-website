RV PHORN PUBG — Website starter (free/manual orders)

FILES
- index.html: responsive Khmer landing page and manual order form.

HOW TO PREVIEW
- Open index.html in a browser. The order form builds a message locally; it does not charge customers or send orders automatically.

BEFORE PUBLISHING
1. Open index.html in a text editor.
2. Near the bottom, find:
   const SHOP = {
     whatsapp: "",
     facebook: ""
   };
3. Add your WhatsApp number in international format with digits only (e.g. Cambodia country code 855, no + sign) and your public Facebook Page URL.
4. Update package names/prices only after confirming actual supplier pricing and availability.
5. Do not add private bank credentials, passwords, or OTPs.
6. Test with a fake order before sharing publicly.

FREE HOSTING
- GitHub Pages can host a static site free on a public repository. Create a GitHub account, create a public repository, upload index.html, then Settings > Pages > deploy from the main branch/root. GitHub's UI may change.
- Alternatively use any free static hosting provider available to you. Free subdomains/usage limits and account requirements may change.
- A custom domain, automated UC fulfillment, a payment gateway, order database, and supplier API are not included.

IMPORTANT
This is a demonstration/manual order website, not an authorized UC reseller connection. Confirm supplier authorization and the game/version supported before accepting payment. Only confirm an order after verifying payment in your bank app.
