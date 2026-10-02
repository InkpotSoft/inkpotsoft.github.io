# InkpotSoft website

Static pages for `https://inkpotsoft.github.io/`.

## Pages

- `/readink/privacy/`: readink privacy policy in English.
- `/` and `/readink/`: intentionally empty until product pages are prepared.

## Publishing

The GitHub repository must be `InkpotSoft/inkpotsoft.github.io`.
In Settings > Pages, choose "Deploy from a branch", branch `main`, folder `/ (root)`.
The `.nojekyll` file makes these static files available without Jekyll processing.
No package installation or build step is required.

## Local preview

Run `python3 -m http.server 8080` in this directory and visit
`http://localhost:8080/readink/privacy/`.

## Policy maintenance

The effective date is 2026-10-02.
Review the policy when app data handling changes.
The contact method currently uses the repository's public GitHub Issues.
Do not request private information through a public issue.
