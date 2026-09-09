# TAZA — Coming Soon

**Repository name:** `taza-coming-soon`

A premium, responsive **Coming Soon landing page for TAZA**, a Bangladesh-based natural and organic food brand.

TAZA is envisioned as a broad FMCG/natural-food brand, beginning with dehydrated fruits and botanical/fruit infusions and eventually expanding into organic pantry and wellness-oriented food products.

## Brand

**TAZA**  
**Domain:** `taza.bd`  
**Market:** Bangladesh  
**Positioning:** Premium • Natural • Modern • Bangladesh-born

### Brand direction

TAZA is intentionally broader than a single product category.

Potential future categories include:

- Dehydrated fruits
- Herbal tea
- Fruit infusions
- Organic honey
- Organic spices
- Nuts & seeds
- Granola
- Natural snacks
- Pantry products
- Gift boxes

---

## Current Page

The current website is a single-page launch/coming-soon experience featuring:

- Premium dark earthy visual direction
- Large editorial TAZA wordmark
- Responsive desktop/tablet/mobile layout
- Animated ambient background elements
- Glassmorphism coming-soon card
- Email notification form UI
- Product-category marquee
- Minimal premium footer
- No external JavaScript framework
- No backend required for the current demo

> **Note:** The email form is currently front-end only. It does not store or send submissions until a backend/email service is connected.

---

## Repository Structure

```text
taza-coming-soon/
│
├── index.html
└── README.md
```

The entire landing page is currently contained in `index.html`.

---

## Run Locally

No build tools are required.

Simply open:

```text
index.html
```

in any modern browser.

For a local development server, you can use:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

---

## GitHub Pages Deployment

This project is designed to work directly with GitHub Pages.

### 1. Create the repository

Recommended repository name:

```text
taza-coming-soon
```

Alternative:

```text
taza-bd-coming-soon
```

Recommended choice:

**`taza-coming-soon`**

Keep the repository name simple because it is only the technical project name; the customer-facing brand remains **TAZA**.

### 2. Upload the files

Upload:

```text
index.html
README.md
```

to the repository root.

### 3. Enable GitHub Pages

In GitHub:

```text
Repository
→ Settings
→ Pages
→ Build and deployment
→ Source: Deploy from a branch
→ Branch: main
→ Folder: / (root)
→ Save
```

GitHub will generate a Pages URL similar to:

```text
https://YOUR-USERNAME.github.io/taza-coming-soon/
```

### 4. Custom domain later

When `taza.bd` is ready to point to the production website, use the GitHub Pages **Custom domain** setting.

The final public URL should be:

```text
https://taza.bd
```

GitHub Pages will handle HTTPS after the DNS configuration has propagated.

---

## Recommended Git Workflow

Initial setup:

```bash
git init
git add .
git commit -m "Initial TAZA coming soon page"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/taza-coming-soon.git
git push -u origin main
```

Future updates:

```bash
git add .
git commit -m "Update TAZA landing page"
git push
```

---

## Design System

### Visual direction

The current design intentionally avoids the stereotypical bright-green "organic food" aesthetic.

The direction is:

- Premium
- Editorial
- Minimal
- Earthy
- Modern
- Calm
- Natural
- Slightly luxurious

### Typography

Primary UI font:

**DM Sans**

Editorial/display font:

**Playfair Display**

### Color direction

The page uses:

- Deep natural green/black background
- Warm cream typography
- Muted botanical green accents
- Subtle gold/natural highlights
- Transparent glass surfaces

The exact palette is defined inside `index.html`.

---

## Content Direction

Current headline:

> **Freshness, preserved.**

Current supporting message:

> From the finest fruits and botanicals to everyday organic goodness — TAZA is creating a new generation of naturally inspired foods, thoughtfully made in Bangladesh.

Current positioning:

> Real Ingredients • Thoughtfully Made • From Bangladesh

These can be changed later as the brand strategy develops.

---

## Product Architecture

A future TAZA product architecture could follow:

```text
TAZA
│
├── TAZA Fruits
│   └── Dehydrated fruits
│
├── TAZA Tea
│   └── Herbal teas
│
├── TAZA Infuse
│   └── Fruit & botanical infusions
│
├── TAZA Organic
│   └── Certified organic products
│
└── TAZA Pantry
    ├── Honey
    ├── Spices
    ├── Nuts
    ├── Seeds
    └── Natural foods
```

This keeps **TAZA** as the master brand rather than limiting the company to dehydrated fruit.

---

## Before Production Launch

The coming-soon page is a brand prototype and should be upgraded before the commercial launch.

Recommended next steps:

### Brand

- Finalize TAZA logo
- Finalize typography
- Establish official color system
- Create packaging identity
- Create brand guidelines
- Verify trademark availability/registration in Bangladesh

### Website

- Connect the email signup form to a real service
- Add social media links
- Add privacy policy
- Add terms if required
- Add favicon
- Add Open Graph/social sharing image
- Add Google/Search Console verification
- Add analytics
- Optimize image assets when photography is introduced

### Product

- Finalize initial SKUs
- Test dehydration parameters
- Establish food-safety procedures
- Conduct shelf-life testing
- Finalize packaging barrier requirements
- Determine batch coding/traceability
- Confirm labeling and regulatory requirements

---

## Future Website Direction

The coming-soon page should eventually evolve into:

```text
Home
│
├── Shop
│   ├── Fruits
│   ├── Tea
│   ├── Infusions
│   └── Organic
│
├── Our Story
├── Ingredients
├── Journal
├── Wholesale
└── Contact
```

The visual language should remain consistent with the launch page.

---

## Important Brand Note

**TAZA is the brand.**

The website and product categories should support the brand rather than define it.

Avoid positioning TAZA permanently as:

> "A dehydrated fruit company"

Prefer:

> **A modern natural-food brand from Bangladesh.**

The initial dehydrated fruit and infusion products are the entry point, not the limit of the brand.

---

## License

All brand-specific design, copy and assets in this repository are intended for the TAZA project.

Do not reuse TAZA branding, logos, product identity or proprietary assets for unrelated projects.

---

## Status

**Project status:** Coming Soon

**Brand:** TAZA  
**Website:** `taza.bd`  
**Repository:** `taza-coming-soon`  
**Country:** Bangladesh

---

### TAZA

**Freshness, preserved.**
