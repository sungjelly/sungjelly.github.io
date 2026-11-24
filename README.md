# Sungjae Lee — research homepage

Personal academic homepage at **https://sungjelly.github.io/**.

## Edit the homepage

The website uses `index.html`, `portrait.svg`, and `bagm-architecture.svg`. It uses plain HTML and CSS, with no installation, build step, JavaScript dependency, analytics, or external fonts.

1. Open `index.html` on GitHub and choose **Edit this file**.
2. Change the text in the About, Selected research, Background, or Elsewhere sections. The colors and responsive layout are defined in the `<style>` block near the top.
3. Commit to `main`. GitHub Pages publishes the updated page automatically.

The profile photo is embedded in `portrait.svg` with its original image data. CSS frames it more tightly on the homepage; clicking the photo opens the full image. To replace it with a new JPG or PNG, upload the new image and change both photo links in `index.html`. Adjust `.portrait img` in the style block if the new photo needs different framing.

The BAGM architecture image is kept in `bagm-architecture.svg`, displayed as a small, uncropped thumbnail beside the project description. Its link opens the full-resolution image, including on mobile.

## Paper

The BAGM entry links to `BAGM_Paper.pdf`. To update the public paper, replace that file while keeping the filename. The posted PDF preserves the page contents of the supplied BAGM manuscript; its stream encoding was converted losslessly to allow publication through GitHub's text editor.

## GitHub Pages configuration

In **Settings → Pages**, use **Deploy from a branch**, branch **main**, folder **/(root)**. The repository name must remain `sungjelly.github.io` to use the address above.

## Suggested next additions

- Add a confirmed current affiliation and the email address you want to make public. The profile section has a comment marking the location.
- Add verified paper metadata or preprint links as available. Do not label a submission as an accepted publication.
- For each project, describe your own contribution, one well-supported result, and the evaluation setting and limitations.

To add a public email link, use `<a href="mailto:YOUR_PUBLIC_EMAIL">Email</a>`.

Keep the page title, description, and footer update date in sync with significant edits. Check both narrow and wide screens after layout changes. The BAGM figure describes the model architecture; it is not an experimental result plot.
