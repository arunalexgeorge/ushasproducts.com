# ushasproducts.com

One-page website for **Usha's Products** — homemade Kerala pickles, spice powders,
coconut oil, cow ghee and snacks.

Live site: https://arunalexgeorge.github.io/ushasproducts.com/

## Structure

```
index.html            the whole page
assets/css/styles.css styling (palette taken from the logo)
assets/img/logo.jpeg  logo
docs/logo.jpeg        original logo source
```

Static HTML/CSS — no build step. Open `index.html` in a browser to preview locally.

## Editing

- **Products** — each item is a `<li class="card">` in `index.html`; copy one to add a product.
- **Contact details** — phone, WhatsApp and email are in the `#order` section of `index.html`
  and are currently **placeholders** (`+91 00000 00000`, `hello@ushasproducts.com`).
- **Colours** — the CSS variables at the top of `assets/css/styles.css`.

## Custom domain

To serve this at `ushasproducts.com`, add a `CNAME` file containing the domain,
point the domain's DNS at GitHub Pages, then set the custom domain in
Settings → Pages.
