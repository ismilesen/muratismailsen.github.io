# Murat Ismail Sen Portfolio Foundation

This version establishes the shared visual system and reusable case-study structure.

## Included

- Updated homepage using the cryptography classroom photo
- Shared design tokens for color, spacing, type, radius, and shadows
- Reusable navigation, buttons, tags, and section styles
- Responsive featured-project layout
- Technical interests and education sections
- Full project case-study template
- GitHub Pages compatible file structure

## Run locally

```bash
python3 -m http.server 8000
```

Open:

```text
http://localhost:8000
```

## Main files

- `index.html`
- `projects/project-template.html`
- `assets/css/tokens.css`
- `assets/css/base.css`
- `assets/css/components.css`
- `assets/css/home.css`
- `assets/css/project.css`
- `assets/js/main.js`

## First project workflow

1. Duplicate `projects/project-template.html`.
2. Rename it with a short URL-friendly name.
3. Replace placeholder project information.
4. Add project images under `assets/images/projects/<project-name>/`.
5. Link the new page from the homepage project card.
6. Test on desktop and mobile.

## Resume

Add Murat's résumé to the root folder as:

```text
resume.pdf
```

## Deployment

This structure can be pushed directly to a GitHub repository and deployed with GitHub Pages.


## Current case studies

- `projects/ucsc-meetup.html`

## Repository workflow

After copying this folder to your Mac:

```bash
git init
git add .
git commit -m "Create portfolio foundation and UCSC Meetup case study"
```


## Featured research case study

- `projects/living-world.html`


## BananaSpice case study

- `projects/bananaspice.html`
- Add the final demo video under `assets/videos/bananaspice-demo.mp4`
