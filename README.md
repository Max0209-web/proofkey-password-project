# ProofKey Password Project

Static educational web project about creating stronger passwords and passphrases. The app runs entirely in the browser and does not send generated passwords to a server.

## Features

- Password generator based on `crypto.getRandomValues`.
- Passphrase mode.
- Strength indicators based on length, character set, entropy-style scoring, and weak-pattern checks.
- Responsive static layout.
- Supporting presentation included in `docs/password-project-presentation.pptx`.

## Stack

- HTML
- CSS
- JavaScript
- Browser Web Crypto API

## Run locally

Open `index.html` in a browser.

## Sources used in the project

- NIST SP 800-63B: https://pages.nist.gov/800-63-4/sp800-63b.html
- NCSC Three random words: https://www.ncsc.gov.uk/collection/top-tips-for-staying-secure-online/three-random-words
- NCSC Password managers guidance: https://www.ncsc.gov.uk/collection/top-tips-for-staying-secure-online/password-managers

## Public snapshot notes

This is a static project. There are no backend credentials, databases, or secrets in the repository.
