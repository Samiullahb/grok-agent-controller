# Grok Agent Controller

GitHub Pages dashboard + GitHub Actions workflow for running Grok tasks securely.

## Enable Pages
Repository **Settings → Pages → Build and deployment → Source: GitHub Actions**.

Site URL:
https://samiullahb.github.io/grok-agent-controller/

## Add the API key
Repository **Settings → Secrets and variables → Actions → New repository secret**.

Name: `XAI_API_KEY`

Never put the key in `index.html`, `app.js`, or any public Pages file.

## Run Grok
Open **Actions → Grok Agent → Run workflow**, enter the task, and choose an action.

The public dashboard currently prepares/copies the task. GitHub Actions performs the authenticated Grok call. A true one-click public trigger requires a server-side authenticated endpoint; a GitHub token must not be embedded in the browser.

## Included
- Dark responsive dashboard
- GitHub Pages deployment workflow
- Manual Grok Agent workflow
- Secure Actions secret reference
- Research / ideas / script / analytics actions
