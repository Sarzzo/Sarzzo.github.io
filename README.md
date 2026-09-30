# Sara Ibrahim — academic website

Personal academic website built with Jekyll and hosted on GitHub Pages.

## Editing the site

| What | Where |
| --- | --- |
| Name, job title, affiliation, email, ORCID and other links | `_config.yml` (the `author:` section) |
| Home page text | `_pages/about.md` |
| CV page | `_pages/cv.md` |
| Publications (one file each) | `_publications/` |
| Talks and posters (one file each) | `_talks/` |
| Teaching (one file each) | `_teaching/` |
| Menu | `_data/navigation.yml` |
| Profile photo | put it in `images/` and set `avatar:` in `_config.yml` |
| Banner image | put it in `images/` and set `banner:` in `_config.yml` |

To add a publication, copy an existing file in `_publications/` and edit it.
In the `authors:` line, write your name as `S. Ibrahim` so that it is shown in bold.

Talks and teaching entries accept an optional `display_date:` (for example
`"January 2026"`) that is shown instead of the exact `date:`.

Every change committed to the main branch is published automatically within a minute or two.
