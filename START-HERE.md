# Federica Giardina — academic website (HugoBlox source)

This is the **editable source** of your site. GitHub builds it automatically.

## One-time deployment
1. In your `federica-giardina.github.io` repo (GitHub Desktop), delete the old
   compiled files and copy ALL files from this folder in their place, then
   commit & push to `main`. (Your old site stays in git history and also remains
   in the `federigia.github.io` repo as a backup.)
2. On github.com: open the repo → **Settings → Pages → Build and deployment →
   Source → "GitHub Actions"**. (This is the only manual setting.)
3. Watch the **Actions** tab — the first build takes a few minutes, then your
   site is live at https://federica-giardina.github.io/

## Editing later
- Your profile (bio, experience, education, skills, languages, awards):
  `data/authors/me.yaml`
- A publication = one folder in `content/publications/` with an `index.md`
- Your CV: replace `static/uploads/resume.pdf`
- Your photo: replace `assets/media/authors/me.png`
Edit, commit, push — the site rebuilds itself.

You can delete this file.
