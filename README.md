# A Philosophical Guide to Organizations

Book landing page for *A Philosophical Guide to Organizations* by Joanna Staniszewska.

**Live site:** https://jstaniszewska-101.github.io/guide-to-organizations-book/

## Setup

Single-page static site — pure HTML + CSS, no build step required.

### To add images

- `book-cover.jpg` — place the book cover image in the root directory
- `joanna.jpeg` — place the author photo in the root directory

Both images degrade gracefully with a placeholder if missing.

### To activate the email form

In `index.html`, find the `<form>` element in the `#notify` section and replace `action="#"` with your Buttondown or Mailchimp endpoint URL, and set `method="post"`.

## Structure

```
index.html   — single-page site
style.css    — all styles
README.md    — this file
book-cover.jpg  — (add manually)
joanna.jpeg     — (add manually)
```
