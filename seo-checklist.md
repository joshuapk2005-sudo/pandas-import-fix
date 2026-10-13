# SEO implementation and launch checklist

Use this checklist to distinguish what is already in the project from what only becomes possible after deployment.

## Implemented in the project

- [x] One useful page with a unique, descriptive title and meta description.
- [x] One clear H1, logical H2/H3 headings, and a linked table of contents.
- [x] Direct answer near the start, concise definition, step-by-step fix, and answer-focused FAQ.
- [x] Natural primary topic and related environment terms; no keyword stuffing.
- [x] Troubleshooting table with symptoms, likely causes, and next steps.
- [x] Python, pip, virtual-environment, IDE, Jupyter, and Conda examples that match the relevant environments.
- [x] Useful internal section links and authoritative external documentation links.
- [x] Semantic HTML, table headers/caption, descriptive navigation labels, skip link, keyboard focus styling, and reduced-motion support.
- [x] Responsive CSS layouts and no external fonts, image downloads, JavaScript, frameworks, or analytics scripts.
- [x] Open Graph type, title, description, and locale metadata.
- [x] `robots.txt` permits crawling; `sitemap.xml` contains a single page entry.
- [x] No structured data added. The page does not need schema to communicate its visible content; schema cannot guarantee rankings, rich results, or AI citations.
- [x] Deployment-specific canonical, sitemap, and robots sitemap URL are documented as placeholders rather than pretending a domain is live.

## Before publishing

- [ ] Choose a GitHub account/repository name and confirm the intended Pages URL.
- [x] Set the canonical, sitemap, and robots sitemap URLs to the expected repository Pages address: `https://joshuapk2005-sudo.github.io/pandas-import-fix/`.
- [ ] Confirm that the URL shown under GitHub **Settings → Pages** matches; update all three URL references if it differs.
- [x] Push the project source to the public `main` branch of `joshuapk2005-sudo/pandas-import-fix`.
- [ ] Enable GitHub Pages for branch `main`, folder `/ (root)` under repository **Settings → Pages**.
- [ ] Review the title, description, public URL, date, and content after the final edits.
- [ ] Test the GitHub Pages preview on desktop and a real or emulated mobile viewport.
- [ ] Check keyboard navigation, visible focus, text zoom, and color contrast in the rendered site.
- [ ] Validate HTML, XML, and local links. Check sitemap and robots URLs on the published site.
- [ ] Confirm GitHub Pages is not blocked by repository visibility/settings or an accidental `noindex` directive.
- [ ] Do not submit the placeholder sitemap or claim the site is indexed.

## After publishing

- [ ] Open the site and confirm CSS loads under the repository URL (a project site usually lives below `/<repository>/`).
- [ ] Open `/robots.txt` and `/sitemap.xml` at the actual published base URL and check they contain no placeholders.
- [ ] Set up Google Search Console and verify ownership.
- [ ] Submit the sitemap in Search Console and inspect the published page URL.
- [ ] Record indexing status and any reported issues without assuming that submission guarantees indexing.
- [ ] Record real Search Console impressions, clicks, CTR, and average position when available.
- [ ] Revisit the page when official package instructions change; update `lastmod` only when the page is materially updated.
- [ ] Do not promise a ranking, traffic, rich result, or AI citation.
