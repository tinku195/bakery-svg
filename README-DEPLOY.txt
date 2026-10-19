BAKERY & CHOCOLATE LANDING PAGE — DEPLOYMENT NOTES

FILES
- index.html: landing page, SEO metadata, product details and checkout links
- styles.css: responsive design
- robots.txt: crawler instructions (update the Vercel URL)
- sitemap.xml: sitemap (update the Vercel URL)
- favicon.svg: browser icon
- images/: put your own preview images here if you update the social preview metadata

YOUR PRODUCT LINKS ARE ALREADY ADDED
Payhip: https://payhip.com/b/6aWhd
Gumroad: https://mammani.gumroad.com/l/eikvh

IMPORTANT BEFORE LAUNCH
1. Replace the illustrative emoji-based hero/cards with previews made from your actual included artwork for the strongest product presentation.
2. Update the sitemap URL and robots.txt sitemap line after your Vercel project URL is known.
3. In index.html, replace /images/social-preview.jpg with a real preview image you create and upload to public/images/social-preview.jpg, or remove the social image tags until ready.
4. Check the wording, file counts, dimensions, and license against your actual downloadable ZIP.
5. Add your real support/contact details and privacy notice if you add analytics, tracking, or a contact form.
6. Do not claim that Google ranking or organic traffic is guaranteed.

DEPLOY USING VERCEL (EASY METHOD)
Option A — GitHub:
1. Create a GitHub repository and upload all files while preserving the folder structure.
2. Sign in to Vercel and choose Add New -> Project.
3. Import the GitHub repository.
4. For a plain static HTML site, leave Framework Preset as Other. No build command is needed; the project root is the folder containing index.html.
5. Deploy and open the generated .vercel.app URL.
6. Update robots.txt and sitemap.xml with the actual URL, commit the changes, and let Vercel redeploy.

Option B — Vercel CLI:
1. Install Node.js and Vercel CLI on your computer.
2. Open a terminal in the folder containing index.html.
3. Run: vercel
4. Follow the prompts. For production, run: vercel --prod

SEO CHECKLIST
- Add the deployed URL as a property in Google Search Console and verify ownership.
- Submit https://YOUR-VERCEL-DOMAIN.vercel.app/sitemap.xml after replacing the placeholder.
- Use URL Inspection to request indexing after deployment. This is a request, not a guarantee.
- Publish useful supporting content, e.g. articles about bakery packaging graphics, using SVG files in Inkscape, and choosing graphics for café menus.
- Share genuine preview pins on Pinterest that link to your landing page.
- Use your own artwork for page images and descriptive alt text.
- Add a custom domain later if you want a memorable brand URL.

The page uses a Google Fonts import. If you prefer no third-party font request, remove the @import line in styles.css.
