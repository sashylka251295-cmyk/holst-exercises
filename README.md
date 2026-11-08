# Holst Exercises

Static, self-checking English exercises designed for embedding in Holst boards.

## Exercises

- [`exercises/vera-word-order/`](exercises/vera-word-order/) — **Put the words in the correct order**: seven sentences practising comparative structures and changes in a neighbourhood.

## Privacy and security

- The site contains no authentication, analytics, external libraries, or network requests.
- Exercise state stays in the learner's browser.
- No Holst profiles, MCP settings, tokens, cookies, or authorization data belong in this repository.
- This repository and its GitHub Pages site are public. Correct answers are stored in the exercise HTML and can be viewed in the page source.

## Add a new exercise

1. Create a lowercase, hyphenated folder under `exercises/`, for example `exercises/new-topic/`.
2. Add a self-contained `index.html` with inline CSS and JavaScript.
3. Keep the exercise free of external libraries, analytics, credentials, and student personal data.
4. Add a relative link to the new exercise in the root `index.html` and in this README.
5. Test the file locally, commit it to `main`, and wait for GitHub Pages to publish the update.

The direct Pages URL for an exercise follows this pattern:

```text
https://sashylka251295-cmyk.github.io/holst-exercises/exercises/<folder>/
```

## Local use

Open either `index.html` directly in a browser. No installation or build step is required.
