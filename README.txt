MFD VISUALS BOOKING SITE — STARTER

Files:
- index.html: complete responsive one-page website.

Current booking behavior:
- Visitors choose a package and fill out a request.
- On submit, the page opens the visitor's email app with a prefilled request addressed to marifrmdab2@icloud.com.
- The visitor must press Send in their email app.
- This is not a server-backed booking system; it does not store requests or block unavailable dates.
- No payment is collected. You review each request and approve it manually.

FREE DEPLOYMENT (GitHub + Cloudflare Pages):
1. Create/sign into GitHub at https://github.com
2. Create a new repository named mfd-visuals-site.
3. Upload index.html to the repository root and commit.
4. Create/sign into Cloudflare at https://dash.cloudflare.com
5. Open Workers & Pages -> Create -> Pages -> connect to Git.
6. Select mfd-visuals-site.
7. For plain HTML, use no framework; leave build command blank and set output directory to / (repository root).
8. Deploy. Cloudflare gives you a public *.pages.dev URL.
9. Test the site on your phone and send a test request to make sure email opens correctly.

Before publishing:
- Confirm marifrmdab2@icloud.com is the right business inbox, or change it in the mailto: line near the bottom of index.html.
- Replace the abstract hero panel with your own licensed/approved video still or portfolio clip if desired.
- Keep package deliverables and turnaround promises realistic.
- If you later want requests saved automatically without opening email, connect a form backend such as Formspree or build a small serverless endpoint. Check its current free-plan limits first.
- A custom domain is optional and usually costs money; the pages.dev address can be used for free.
