# VYNDORA Virtual City Life — prototype

## Upload
Upload all files and folders in this package to the root of the existing `vyndora` GitHub repository. Keep the folder structure exactly as shown:
- `index.html`
- `character.html`, `world.html`, `neighbourhoods.html`, `properties.html`, `home-confirmation.html`, `life.html`, `business.html`
- `assets/style.css`
- `assets/app.js`

Commit the changes, then open `https://peaceiyama5-cyber.github.io/vyndora/`.

## Included and working in this prototype
- Separate HTML pages and navigation
- Character profile form saved in this browser using localStorage
- City selection and Lagos neighbourhood selection
- Rent/buy sample property listings and confirmation
- Lagos local clock
- Demo life hub and business/partnership information pages
- Mobile-friendly layout

## Not connected yet
This is NOT a finished production multiplayer game. There is no secure login, shared player database, multiplayer, 3D model viewer, server-side wallet, real V-Coins, purchases, ad network, sponsorship payment processing, jobs economy or live city simulation. The sample property prices and balances are placeholders. Do not accept payments or promise players ownership based on this demo.

## Next engineering phases
1. Connect Supabase Auth and database with row-level security.
2. Add the existing licensed 3D character models and character viewer.
3. Build server-authoritative wallets and transactions; never store real balances in browser code.
4. Add multiplayer/game server and persistence.
5. Integrate platform-compliant payments and ad networks after deployment target is selected.
