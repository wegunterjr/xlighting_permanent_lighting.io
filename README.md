# X Lighting — Spark V1

Sales site for the Utah-designed, USA-assembled 36V 4-channel WLED controller.

Live: https://wegunterjr.github.io/xlighting_permanent_lighting.io/

Spark V1 was designed by a student who loves soldering, lacrosse, and making money: a unique native-36V 4-channel WLED controller for Govee Pro and a few other high-power strings, with an onboard true-off relay. Assembled in the USA. $199 + shipping via Stripe.

Buy: $199 + shipping → [Stripe](https://buy.stripe.com/8x29AU9YF0rxcri8dI7ss05)

## Publish (GitHub website)

1. Open [the repo](https://github.com/wegunterjr/xlighting_permanent_lighting.io)
2. Click **Add file → Upload files**
3. Drop in everything in this folder (`index.html`, `favicon.svg`, `og.jpg`, `images/`, `.nojekyll`)
4. Replace the old `index.html` when GitHub asks
5. Commit to `main`

GitHub Pages should already be on: **Settings → Pages → Deploy from branch `main` / `/ (root)`**. The site updates in about a minute.

## Orders

Buy buttons go to the Stripe Payment Link in `index.html` (`const STRIPE` and every `buy.stripe.com` href).

**Before you publish a price change:** Stripe → Payment links → edit or create a new link for Spark V1 at the displayed price + shipping → paste the new `https://buy.stripe.com/...` URL into `index.html`. Buy checkout: https://buy.stripe.com/8x29AU9YF0rxcri8dI7ss05 ($199). The checkout price must match the page.

## Just send money

**Just send money** buttons use `const SUPPORT` in `index.html`. Until you paste a Stripe link there, they open an email to info@utahlightcontrollers.com.

To take money with no controller and no shipping:

1. Stripe → **Payment links** → New
2. Name it **Just send money**
3. No shipping. Let the customer pick an amount if Stripe offers that, or set **$25** with quantity adjustable so they can send $25 / $50 / $100
4. Copy `https://buy.stripe.com/...` into `const SUPPORT` in `index.html`

Questions land at **info@utahlightcontrollers.com**.
