# ABOLIFE ASAANA Website

A responsive, functional single-page ordering MVP for Janet Ntsiful (Abolife) in Alajo, Accra.

## Run locally
Open `index.html` directly in a browser, or serve the folder with any static server.

## Deploy to Vercel
1. Create a GitHub repository.
2. Upload the contents of this folder.
3. In Vercel, import the repository.
4. Framework preset can be `Other` because this is a static HTML/CSS/JS site.
5. Deploy.

## Owner photo
The actual owner photo was not available in the conversation files. Add the real, unedited photo as:
`assets/janet.jpg`
The website automatically displays it in the hero and About section.

## Editing prices
Open `index.html` and find the `products` array. Set each product's `price` to the current amount in Ghana cedis.

Example:
`price: 20`

The site intentionally shows "Price to be confirmed" while prices are 0, rather than inventing prices.

## Business hours
Edit the `hours` array in `index.html`.

## Functional features
- Responsive navigation and mobile menu
- Homepage search with Enter support
- Product filtering and price sorting
- Quantity controls
- Multi-step-style order modal
- Pickup/delivery selection
- Form validation
- Order summary and request reference
- WhatsApp message generation
- Call link
- Google Maps directions link
- Floating WhatsApp button
- Confirmation state
- Accessible labels/focus states
- Reduced-motion support
- Responsive product grid
- No fake payment processing
