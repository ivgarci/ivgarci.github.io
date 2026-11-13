# ivangarciacobo.com

Personal academic and professional website of **Iván García Cobo**.

- Live site: https://ivangarciacobo.com
- Primary contact: ivan.garcia.cobo@uva.es
- Public research source code: https://github.com/ivgarci/qkd-net-tools
- Framework: Jekyll with Academic Pages theme components

## Editorial sources

Professional and academic biographical data are grounded in the author's **FECYT CVN dated 13 November 2026**. The public LinkedIn profile is used for supplemental public information such as LFCE certification. The website intentionally excludes identification numbers, birth date, private phones, and home address.

The downloadable CVN PDF has **not** been uploaded to the site because it contains personal information.

## Site files

| Page | Source |
| --- | --- |
| About | `_pages/about.md` |
| Research | `_pages/research.md` |
| Publications | `_pages/publications.html`, records in `_publications/` |
| Teaching | `_pages/teaching.html` |
| Projects | `_pages/projects.md` |
| CV | `_pages/cv.md` |
| Writing | `_pages/writing.md` |

Settings: `_config.yml` and `_data/navigation.yml`. The machine-readable CV data in `_data/cv.json` are also kept aligned with the public profile.

## Publications policy

Only records grounded in the FECYT CVN are included in the published bibliography. Research manuscripts are listed separately and never described as accepted or published without evidence. **Only public repositories are linked**; the main QKD code reference is `qkd-net-tools`.

## Deployment

The repository uses the **Deploy Academic Pages template site to Pages** GitHub Actions workflow. In Settings → Pages, the build source should be **GitHub Actions** to avoid a redundant failing branch-build workflow. The custom domain is `ivangarciacobo.com` (see `CNAME`). A 301 HTTPS redirect for `ivangarciacobo.es` must be configured separately at IONOS.

## Backup

The state immediately before the CVN-driven review is preserved in branch `backup-before-cvn-review-2026-11-13`. The earlier pre-upstream backup is in `backup-before-academicpages-refresh-2026-11`.

## Visual branding and publishing

The IGC monogram is used in the SVG favicon, PNG icons and ICO file. The social preview is `images/og-image.png` (1200 × 630), and the profile image is `images/Ivan-Garcia-Cobo.jpg`.

**GitHub Pages source:** under Settings → Pages, select **GitHub Actions**. This administrative setting cannot be changed by repository files; otherwise GitHub may run an additional legacy build which fails even when the Jekyll Action deployment is successful.

The Writing page and its Amazon link remain unchanged.
