# Federica Giardina — academic website

Source of <https://federica-giardina.github.io/>. It is built with [Hugo](https://gohugo.io/)
using a small custom theme in `layouts/` and `assets/css/main.css`. There are no theme
modules and no Node/Tailwind. GitHub Actions builds and deploys every push to `main`
(see `.github/workflows/`). The Hugo version is set in `hugoblox.yaml`.

## Where to edit

| What | File |
| --- | --- |
| Name, role, bio, links, positions, education | `data/profile.yaml` |
| Supervised PhD candidates, postdocs and students | `data/supervision.yaml` |
| Grants, fellowships and travel awards | `data/funding.yaml` |
| Courses and teaching photos | `data/teaching.yaml` (photos in `static/images/teaching/`) |
| Leadership and service roles | `data/leadership.yaml` |
| Book chapters and submitted manuscripts | `data/other_outputs.yaml` |
| Journal articles | one folder per paper in `content/publications/` |
| Talks | one folder per talk in `content/events/` |
| CV PDF | `static/uploads/CV_Giardina_2026.pdf` |
| Portrait | `static/images/federica-giardina.png` |

### Adding a publication

Create `content/publications/<year>-<short-name>/index.md`:

```yaml
---
title: Title of the paper
authors: [Surname AB, me, Other CD]   # "me" is shown as Giardina F, in bold
date: '2026-01-01'
publication:
  name: Journal name
  volume: 12
  issue: 3
  pages: e0001
doi: 10.xxxx/xxxxx
featured: true      # also show it on the home page
---
```

Add `preprint: <url>` for a preprint link. If an author is listed with a matching
`pub_name` in `data/supervision.yaml`, the site underlines their name and lists the
paper under that person on the Supervision page.

## Local preview

```bash
hugo server
```
