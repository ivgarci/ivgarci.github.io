# ivangarciacobo.com — Iván García Cobo

Personal, academic and professional website of **Iván García Cobo**.

- **Live URL:** https://ivangarciacobo.com
- **GitHub Pages repository:** https://github.com/ivgarci/ivgarci.github.io
- **Framework:** Jekyll 4 + [Academic Pages](https://github.com/academicpages/academicpages.github.io), with upstream theme components refreshed in November 2026.
- **Content language:** English.

## Structure

| Section | Source |
| --- | --- |
| Home / About | `_pages/about.md` |
| Research | `_pages/research.md` |
| Publications | `_pages/publications.html` + `_publications/` |
| Teaching | `_pages/teaching.html` |
| Projects | `_pages/projects.md` |
| CV | `_pages/cv.md` |
| Personal writing | `_pages/writing.md` |

Site identity, author details, social links and theme are configured in `_config.yml`. Main navigation is in `_data/navigation.yml`.

## Updating the site

Edit the Markdown pages and collection records, commit to `master`, and review deployment in the **Actions** tab. The Pages workflow builds with Jekyll and deploys the result to GitHub Pages.

## Custom domain

The repository contains `CNAME` with `ivangarciacobo.com`; keep the matching DNS records configured at the domain registrar. Redirect `ivangarciacobo.es` to the canonical `.com` URL using the registrar's HTTPS redirect facility (outside this repository).

## Editorial policy

- Distinguish peer-reviewed publications, preprints and unpublished research manuscripts.
- Include DOI or stable publisher links where available.
- Describe geographically realistic QKD research models as *designs and simulations*, not as actually deployed infrastructure.
- Do not publish sensitive university operational details, passwords, personal records or private project documents.

## Backups

A pre-refresh branch was created as `backup-before-academicpages-refresh-2026-11` before the template update.
