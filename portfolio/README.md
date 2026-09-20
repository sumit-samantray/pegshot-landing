# Sumit Samantray portfolio

This is a standalone static portfolio site intended for `https://sumit-samantray.com`.

It intentionally lives in `portfolio/` so the existing GitHub Pages root for PegShot can remain at `https://pegshot.sumit-samantray.com` without disruption.

## Deploying the portfolio without moving PegShot

Deploy this `portfolio/` directory as a separate **Cloudflare Pages** project:

1. In Cloudflare, open **Workers & Pages → Create application → Pages → Connect to Git**.
2. Select the `sumit-samantray/pegshot-landing` repository.
3. Use no build command and set **Build output directory** to `portfolio`.
4. Deploy the project, then add `sumit-samantray.com` as its custom domain.
5. In Cloudflare DNS, point the apex domain to the Pages project as instructed by the Pages custom-domain flow.

Keep the existing GitHub Pages configuration and `CNAME` file unchanged: it continues to serve the PegShot landing page on `pegshot.sumit-samantray.com`.

The contact email and career details were sourced from the owner-provided résumé. Update `index.html` directly when the résumé changes.
