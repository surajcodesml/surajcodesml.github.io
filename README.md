# surajcodesml.github.io

My personal portfolio — live at [surajcodesml.github.io](https://surajcodesml.github.io).

Single-file site: all HTML, CSS, and JS live in `index.html`. No build step, no dependencies.

## Editing

- **Content** — everything is plain HTML in `index.html`. Timeline stations are in the `<section id="timeline">` block; each one is a self-contained `<div class="station">`.
- **Photos** — drop images into `photos/`, then find the matching `<!-- To show a real photo here -->` comment in `index.html` and swap the placeholder `<div class="tl-photo">` for the `<img>` line shown in the comment. Three spots are ready: symposium, graduation, Hackabull.
- **Resume** — replace `resume.pdf` with the latest version, keep the filename.
- **Colors** — all colors are CSS variables at the top of the `<style>` block (`:root` for light, `[data-theme="dark"]` for dark).

## Deploying changes

```bash
git add .
git commit -m "update"
git push
```

GitHub Pages redeploys automatically in about a minute.
