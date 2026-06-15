# Le Li Academic Homepage

This is a lightweight static academic homepage designed for GitHub Pages.

## Quick deployment

1. Create a GitHub repository named:

   ```text
   layla95-git.github.io
   ```

2. Upload all files in this folder to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select:

   ```text
   Source: Deploy from a branch
   Branch: main / root
   ```

5. The homepage will be available at:

   ```text
   https://layla95-git.github.io/
   ```

## Add a profile photo

Put a photo at:

```text
assets/img/profile.jpg
```

Then in `index.html`, replace the `avatar-placeholder` block with the commented `img` line.

## Add a CV

Put the CV file at:

```text
assets/pdf/cv.pdf
```

Then uncomment the `Download CV` button in the profile card.

## Add code links for publications

When a code repository is ready, add a button in the corresponding publication block, for example:

```html
<p class="pub-links">
  <a href="https://doi.org/..." target="_blank" rel="noopener">DOI</a>
  <a href="https://github.com/layla95-git/example-code" target="_blank" rel="noopener">Code</a>
</p>
```

Do not show empty Code buttons before the repositories are available.
