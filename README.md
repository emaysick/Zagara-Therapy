# Zagara Therapy — static website

## Included files
- `index.html` — simplified homepage
- `styles.css` — shared styling
- `ocd-therapy.html` — dedicated OCD/ERP page
- `anxiety-emdr.html` — dedicated anxiety and EMDR page
- `about.html` — About Emily page
- `faq.html` — fees and FAQs

## Deploy
Upload these files to the root of the connected GitHub repository, replacing the existing `index.html` and adding the new files. Keep the repository's existing README if you prefer. Cloudflare Pages should deploy automatically after the changes are committed to `main`.

## Before public launch
1. In December, configure Sessions Health, replace the temporary Client Access link (`faq.html#client-access`) with the actual client portal login URL, and connect the free consultation CTA to the actual booking URL.
2. Confirm the practice email/contact details and add them consistently.
3. Add an approved professional photo if desired; the current layout intentionally avoids showing a fake or placeholder portrait.
4. Review all copy, clinical descriptions, fee/superbill policy, cancellation policy, and legal/privacy pages with appropriate professional guidance. Confirm the billing code used in your workflow before publishing code-specific insurance guidance. Provide Good Faith Estimates when required and keep the website notice prominent.
5. Add Privacy Policy, Website Disclaimer, 404, `robots.txt`, and `sitemap.xml` pages/files before launch.
6. The intended custom domain is `zagaratherapy.com`. Connect it to the Cloudflare Pages project and verify DNS/SSL before launch.
7. Test all links, mobile layout, keyboard focus, contrast, and metadata after deployment.

The website is a static HTML/CSS site. No framework or build command is required. Do not add client information, credentials, or confidential records to the repository.


## Temporary pre-launch search restriction

All five HTML pages currently include `<meta name="robots" content="noindex, nofollow">` to discourage search indexing before the planned January 2027 launch. This does not make the website private. Remove this directive from every page only when you are ready to launch, and then verify indexing and sitemap settings.

## Temporary contact arrangement

The site currently lists `emily@zagaratherapy.com` as a mailto contact and explains that online consultation booking will be available closer to launch. Connect the Sessions Health booking link when the account is ready. Email copy asks prospective clients not to send sensitive clinical details.


## Legal pages and pre-launch status

- Added `privacy.html` and `disclaimer.html`.
- Added small footer links to the Privacy Policy and Website Disclaimer on all seven HTML pages.
- Kept `<meta name="robots" content="noindex, nofollow">` on all seven pages for the pre-launch period. Remove this directive from every page when ready to launch publicly; it is not a privacy or access-control feature.
- The Privacy Policy is a website-focused draft based on the current static site setup. Review and update it if you add scheduling, analytics, forms, embedded tools, or other third-party services.
- These pages are practical drafts, not legal advice. Review them for accuracy before launch. A website Privacy Policy is not a substitute for a HIPAA Notice of Privacy Practices when one is required.
- The Good Faith Estimate information on the website does not replace the obligation to provide an actual estimate when required.

## Zagara brand update

- Updated public-facing practice name and page/social titles to Zagara Therapy.
- Added the primary tagline “Already whole, already becoming.” to the homepage while preserving the approved hero headline and supporting phrase.
- Added the name meaning and “a small nod to my heritage” explanation to the About page.
- Updated the OCD page closing sentence to connect treatment with making room for uncertainty and moving toward what matters.
- The previous practice email and domain references may still need replacement once the exact purchased domain and email address are supplied.
