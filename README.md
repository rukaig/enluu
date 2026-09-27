# Midnight Love

A static vampire-themed gift site with a password-gated photo scrapbook, a rotating familiar preview, and a separate flower garden.

## Features

- The photo vault opens with passphrase `0223`; its categorized thumbnail rail controls the rotating photo preview.
- Cat, Dog, Bunny, Turtle, and Deer open a centered character preview.
- The flower garden opens with passphrase `balmund` and includes six personality-inspired flowers.
- A beauty appreciation letter and a small gift note accompany the experience.

## Run Locally

Run `npm install`, then `npm start`. The local server opens the `src` site.

## Publish with GitHub Pages

The repository-root `index.html` forwards to `src/index.html`. In **Settings > Pages**, publish from the root of your main branch.

Both passphrases are checked in browser-side JavaScript. They hide content in the interface but do not protect files in a public repository. Do not publish sensitive photos this way.