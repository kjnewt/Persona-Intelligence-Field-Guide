# Persona Intelligence Field Guide

An interactive call-preparation guide for exploring customer roles, business pressures, performance measures, capability conversations, and discovery questions.

## Open the guide

Open `index.html` in a modern browser. There is no build step, package installation, API key, or server-side code.

Choose an industry, use **Browse Personas** to jump to a role, or use the previous and next buttons. Left and right arrow keys and horizontal touch swipes also navigate the personas. Escape closes the persona index.

## Upload to GitHub

1. Extract this ZIP on your computer.
2. Open or create the GitHub repository you want to use.
3. Upload the extracted files to the repository root, with `index.html` at the top level. Upload the files rather than the ZIP itself or an enclosing folder.
4. Commit the uploaded files.
5. Configure GitHub Pages to publish the branch containing these files, using its root directory as the publishing source.
6. Open the Pages URL provided by GitHub after deployment completes.

GitHub Pages availability and access controls depend on your account and organization settings. Confirm the published site's audience before using it for internal material; a private repository alone does not guarantee a private website.

For an existing repository, keep unrelated files and replace only the field guide files as needed.

## Files

- `index.html` — complete guide, including all styles, scripts, and persona content.
- `.nojekyll` — identifies the package as a plain static site.
- `README.md` — setup and maintenance instructions.

## Dependencies and data

The guide uses Google Fonts for Open Sans. If unavailable, it falls back to Arial or the browser's sans-serif font. No other external assets or services are required by the supplied guide. It does not submit learner responses, store progress, or include an evaluation service.

## Update the guide

Edit `index.html`. Persona content is in the `guideData` object; styling is in the `<style>` block; rendering and navigation are in the final `<script>` block. Commit the updated file to the publishing branch to update the deployed guide.

The uploaded HTML has been preserved without content or behavior changes and renamed to `index.html` for static hosting.
