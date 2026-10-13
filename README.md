# InkpotSoft website

Static pages for `https://inkpotsoft.github.io/`.

## Pages

- `/inkycard/`: InkyCard product information, GPL license notices, and contact information in English.
- `/inkycard/support/`: InkyCard setup guidance, troubleshooting, and support email.
- `/inkycard/privacy/`: InkyCard privacy policy covering local data and optional connections.
- `/inkycard/LICENSE.txt`: the full GNU General Public License version 3.
- `/readink/support/`: readink support, contact information, and usage guidance in English.
- `/readink/privacy/`: readink privacy policy in English.
- `/` and `/readink/`: intentionally empty until product pages are prepared.

## Publishing

The GitHub repository must be `InkpotSoft/inkpotsoft.github.io`.
In Settings > Pages, choose "Deploy from a branch", branch `main`, folder `/ (root)`.
The `.nojekyll` file makes these static files available without Jekyll processing.
No package installation or build step is required.

## Local preview

Run `python3 -m http.server 8080` in this directory and visit
`http://localhost:8080/inkycard/`, its `support/` and `privacy/` pages,
`http://localhost:8080/readink/support/`, or
`http://localhost:8080/readink/privacy/`.

## Policy maintenance

InkyCard policy effective date: 2026-10-13. Readink policy effective date: 2026-10-02.
Review each policy when its app data handling changes.
InkyCard support and privacy requests use `inkpotsoft@icloud.com`.
Do not request passwords, API keys, or unrelated private information in support reports.
