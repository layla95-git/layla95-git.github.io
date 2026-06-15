# Le Li Academic Homepage: Jekyll Version

This package is a clean Jekyll-style academic homepage for `layla95-git.github.io`.
It uses Le Li's information only. It does not contain personal information from the referenced example homepage.


## Language

This version is fully English. No Chinese display name or Chinese page text is included.

## Main Pages

- `index.html`: Home
- `index_layout2.html`: Home (Layout 2)
- `publications.html`: Publications
- `showcase.html`: Showcase

## Key Content Files

- `_data/profile.yml`: personal information, education, experience, awards, academic service, research interests
- `_data/news.yml`: News and Updates
- `_publications/*.md`: publication records
- `_showcase/*.md`: future showcase/project items. This folder is currently empty except for `.gitkeep`.
- `assets/images/photos/Profile.jpg`: profile photo
- `assets/images/publications/`: optional publication thumbnails for Selected Publications and Publications
- `assets/css/style.css`: visual style

## What to replace

1. Replace `assets/images/photos/Profile.jpg` with your real photo if needed.
2. Add DOI, paper, code, and project links later in `_publications/*.md`.
3. Add a CV PDF later at `assets/pdf/cv.pdf` and then add a CV link in `_data/profile.yml` or the profile card.
4. Showcase is intentionally left empty for now. Add `_showcase/*.md` files later when you want to display research demos, slides, videos, or code repositories.
5. Optional publication thumbnails can be placed in `assets/images/publications/`. To display one, add `thumbnail: "/assets/images/publications/your-image.jpg"` to the corresponding `_publications/*.md` front matter.

## Upload to GitHub Pages

Upload all files and folders in this package to the root of the repository `layla95-git.github.io`.
Then go to:

Settings -> Pages -> Build and deployment -> Source: Deploy from a branch -> Branch: main -> Folder: /root -> Save

The site will be available at:

https://layla95-git.github.io/


## Newly added DOI links

The following DOI links are included in the corresponding publication files:

- IEEE TCNS 2025: `10.1109/TCNS.2024.3431414`
- IEEE TASE 2024: `10.1109/TASE.2023.3326347`
- ISA Transactions 2023: `10.1016/j.isatra.2023.08.017`
- Nonlinear Dynamics 2023: `10.1007/s11071-022-07980-9`

## Optional publication thumbnails

If you want a Selected Publication item to show a left-side image, place the image in:

```text
assets/images/publications/
```

Then add this line to the front matter of the corresponding publication file:

```yaml
thumbnail: "/assets/images/publications/example.jpg"
```

Recommended image size: approximately `600 x 400 px` or any 3:2 / 4:3 image. The CSS will crop it neatly.
