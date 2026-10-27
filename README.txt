# StudyMate AI — SEO optimization package

## Files
- `index.html`: updated title, meta description, canonical URL, Open Graph/Twitter tags, and Organization JSON-LD.
- `sitemap.xml`: sitemap for the one-page public site.
- `robots.txt`: allows crawling and points to the sitemap.
- `og-image.png`: 1200×630 social sharing image referenced by the metadata.

## Deploy to Netlify
Upload/deploy the contents of this folder as the site publish directory, or replace these files in your existing project and redeploy. Ensure all four files are at the site root.

Live site: https://fantastic-medovik-41d0b4.netlify.app/

## Validation after deployment
1. Open `https://fantastic-medovik-41d0b4.netlify.app/robots.txt` and confirm it displays the robots rules.
2. Open `https://fantastic-medovik-41d0b4.netlify.app/sitemap.xml` and confirm it displays the XML sitemap.
3. Open `https://fantastic-medovik-41d0b4.netlify.app/og-image.png` and confirm the image loads.
4. Run the URL through Google's Rich Results Test. The Organization schema may validate as structured data but does not necessarily create a rich result.
5. Test the URL in Facebook Sharing Debugger or LinkedIn Post Inspector to inspect social preview.
6. In the browser, View Page Source and confirm one `<h1>` and the metadata are present.

Note: validation screenshots must be captured from the actual tools after the updated site has been deployed. This package does not claim those external checks have already passed.
