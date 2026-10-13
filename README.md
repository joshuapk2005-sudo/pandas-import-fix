# PyFix Guide: No module named pandas

A lightweight, responsive troubleshooting page and SEO/AEO practice project. The website uses only HTML and CSS. No framework, JavaScript, analytics, or external asset is required.

## Project files

- `index.html` — the help article and page metadata.
- `styles.css` — responsive layout, typography, and focus styles.
- `robots.txt` — crawler access rules and a sitemap URL set for the expected GitHub Pages address.
- `sitemap.xml` — one-page sitemap set for the expected GitHub Pages address.
- `keyword-research.md` — qualitative keyword comparison and source limitations.
- `seo-checklist.md` — implementation and launch checklist.
- `seo-report-template.md` — a blank evidence/report template.
- `resume-project-summary.md` — portfolio summary that separates implementation from measured results.

## Preview locally

The page has no build step or dependencies. From this folder, open `index.html` in a browser. For a local HTTP preview if Python is installed, run:

```text
python -m http.server 8000
```

Then open `http://localhost:8000`. Press Ctrl+C in the terminal to stop the local server. If the `python` command is unavailable, open the HTML file directly or use an existing local static-file server.

## Publish with GitHub Pages

The public repository `joshuapk2005-sudo/pandas-import-fix` exists and was empty when checked. Source files still need to be pushed, and GitHub Pages still needs to be enabled in repository settings.

1. Upload the contents of this project folder to the repository root, or push them with Git:

   ```text
   git init
   git add .
   git commit -m "Build pandas troubleshooting guide"
   git branch -M main
   git remote add origin https://github.com/joshuapk2005-sudo/pandas-import-fix.git
   git push -u origin main
   ```

   If the local project already has Git initialized or a remote configured, inspect it before repeating those commands. Authenticate through Git's normal credential manager; never put a password or token in project files or commands.
2. In the repository, open **Settings → Pages**. Select **Deploy from a branch**, choose `main` and `/ (root)`, then save. This account setting still needs to be enabled.
3. Wait for the Pages deployment to finish. The expected project URL is `https://joshuapk2005-sudo.github.io/pandas-import-fix/`; confirm the actual URL under **Settings → Pages**.
4. Open the published URL and check that the page and stylesheet load. Also open `/robots.txt` and `/sitemap.xml` below the published site base.

### Confirm the canonical and sitemap URLs

The canonical URL, sitemap `<loc>`, and robots sitemap directive are set to the expected Pages address:

After enabling Pages, confirm that GitHub shows this exact URL. If the repository is renamed or a custom domain is used, update all three URLs before redeploying. GitHub Pages does not automatically rewrite canonical or sitemap URLs.

The repository slug is `pandas-import-fix`; it is a descriptive project name, not evidence of search performance.

## Set up Google Search Console

Do this only after the site is publicly accessible:

1. Open [Google Search Console](https://search.google.com/search-console/) and add the exact published site. Choose a URL-prefix property if verifying only the Pages URL; follow Google's current verification choices. A DNS-based Domain property requires control of the domain.
2. Complete ownership verification using one of Google's offered methods. For GitHub Pages, an HTML file or HTML meta tag may be possible if supported by the current verification flow; add and publish it in the repository if needed. Do not put credentials or private tokens in the project.
3. In Search Console's **Sitemaps** report, submit the actual sitemap URL and check for processing/errors. Submission does not guarantee crawling or indexing.
4. Use **URL Inspection** for the exact published page to see what Google reports and, if available, request indexing. A request is not an indexing guarantee.
5. Later, use **Performance → Search results** to record impressions, clicks, CTR, and average position for a defined date range. Record the date range and filters in `seo-report-template.md`. New sites/pages may have no data for a while.
6. Review indexing and page experience information when available; address actual reported issues and document the change. Do not report rankings, traffic, or AI citations that you have not observed and recorded.

Analytics is optional for this small content page. If you later choose an analytics product, review its privacy requirements and consent obligations for your audience and location. This project intentionally includes no analytics tags or tracking by default.

## Keyword research and measurement

The topic was selected using qualitative reasoning, not invented volume or difficulty metrics. Available search pages did not provide a reliable, current competitor sample. See `keyword-research.md` for candidate topics, intent, sources, date, and limitations. Use `seo-report-template.md` to record future real-world evidence, and `seo-checklist.md` before and after launch.

## Current verification status

- The public GitHub repository exists. GitHub Pages deployment and the live URL still need to be confirmed in repository settings.
- Search Console property has not been set up.
- Python was not available in the environment where the project was authored, so the Python examples have **not** been executed here.
- Perform the checks listed in `seo-checklist.md` and update `resume-project-summary.md` only with tests actually run and results actually measured.
