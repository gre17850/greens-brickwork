# Green's Brickwork & Building — Website

Single-page website for a Basingstoke-based brickwork and building business covering Hampshire, Berkshire, Windsor and surrounding areas.

## Tech
- Plain HTML/CSS/JS (no build step)
- Inter font from Google Fonts
- Web3Forms for the contact form (free tier)
- Deployable to Vercel as a static site

## Files
- `index.html` — the whole site (HTML + CSS + JS inline)
- `robots.txt` — search engine instructions
- `sitemap.xml` — one URL, helps Google crawl
- `README.md` — this file

## Before going live, do these things

### 1. Get a free Web3Forms access key (for the contact form)
1. Go to https://web3forms.com
2. Type your real email address into the box, click "Create Access Key"
3. Check your email and copy the access key
4. In `index.html`, search for `YOUR_WEB3FORMS_KEY_HERE` and replace with your key
5. Form submissions will arrive at the email you entered

### 2. Confirm the email address shown on the site
Search for `enquiries@greensbrickwork.co.uk` and replace with the real address.

### 3. Add real photos (optional)
The hero shows a brick-pattern placeholder. To add a real photo, drop a `hero.jpg` into this folder and swap the placeholder div in `index.html` for `<img src="hero.jpg" ...>`.

## SEO already in place
- Title tag and meta description targeting "bricklayers Basingstoke" + service area
- Open Graph and Twitter card tags
- Schema.org `GeneralContractor` JSON-LD with service area, opening hours, services
- Schema.org `FAQPage` JSON-LD (helps Google + AI search engines)
- Canonical URL, robots.txt, sitemap.xml
- Mobile-responsive, fast load (no heavy libraries)

## Custom domain (when ready)
Once on Vercel you can buy a domain (e.g. `greensbrickwork.co.uk`) from any registrar and point it at the Vercel project (~£10/year). Update canonical URL, og:url, sitemap.xml and robots.txt to the new domain afterwards.
