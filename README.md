# Backlink CRM

Single-file HTML/CSS/JS CRM for SpotEasy to track backlink outreach to local businesses. Each lead moves through a pipeline from first contact to an acquired backlink.

## Live

https://greglee722.github.io/spoteasy-crm/

## Architecture

- **Frontend:** single `index.html` — HTML + CSS + JS in one file (plus `logo.png`)
- **Database:** Google Sheets (Sheets API v4)
- **Hosting:** GitHub Pages (static)
- **Auth:** Google OAuth 2.0 (Google Identity Services), restricted to the SpotEasy team via an email allowlist

## Deployment

Any push to `main` automatically publishes to GitHub Pages within ~30 seconds.

## Version

The current app version is shown in the header logo (`vX.X`). Full history is in `git log`.
