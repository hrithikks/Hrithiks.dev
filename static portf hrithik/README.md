# Hrithik singh static portfolio

This ZIP is a standalone snapshot of the portfolio content that was published when it was exported.

## Hosting

Upload the extracted files to any static host: GitHub Pages, Netlify, Cloudflare Pages, Render Static Sites, or ordinary shared hosting. The entry point is `index.html`.

## Included public behaviour

The export includes responsive layout, desktop and mobile navigation, the command palette (`Ctrl/Cmd + K`), smooth scrolling, read-more dialogs, keyboard/modal close controls, go-to-top button, public social links, theme settings and Getform contact delivery.

## Images and contact form

Image URLs remain external references. `public/images/image-urls.json` records them; no Cloudinary files are downloaded. You may add local replacements in `public/images` later and update the corresponding URL/reference.

The static contact form can post only to the saved Getform endpoint. The CMS database inbox needs the ASP.NET API, so it is not present in a static export.

To publish later CMS changes, export a new ZIP and replace the hosted files.