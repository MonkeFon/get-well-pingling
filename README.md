# Get Well Soon, Pingling

A small get-well card for Pingling, hosted on GitHub Pages.

**Live:** https://monkefon.github.io/get-well-pingling/

## What is on the page

- A warm, animated card with a personal message
- Floating hearts and petals in the background
- A "Send me a hug" button that bursts hearts and shows a random sweet note (hug count is remembered in the browser)
- Mobile-friendly; animations are disabled for users who prefer reduced motion

## Editing the message

Everything lives in a single file, `index.html`:

- The heading, message and signature are in the `<main class="card">` block.
- The random notes shown by the hug button are in the `notes` array inside the `<script>` block.
- Colours are CSS variables at the top of the `<style>` block.

No build step. Push to `main` and GitHub Pages redeploys automatically.

## Files

| File         | Purpose                                              |
|--------------|------------------------------------------------------|
| `index.html` | The whole site (markup, styles and script)           |
| `.nojekyll`  | Tells GitHub Pages to serve files as-is (no Jekyll)  |
