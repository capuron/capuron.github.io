# Jane Yeung — Portfolio

A single-page portfolio site, hosted free on **GitHub Pages**. No build step — it's one
`index.html` with embedded CSS, so it works the moment Pages is enabled.

It presents Jane Yeung's localization leadership profile (Crypto.com, Google, Apple),
languages, skills, and education — plus a "Projects" section showcasing AI/web systems
built hands-on. **Year/date ranges are intentionally omitted.**

## Already filled in
- Name, tagline, location (Chiang Mai)
- Experience, skills, languages, education — pulled from the CV, no dates
- Contact: email + LinkedIn + GitHub

## Privacy note — phone number left OUT on purpose
Your CV lists a personal mobile (+66 …). I did **not** put it on the page, because a phone
number on a public, search-indexed site invites spam/scam calls. Email and LinkedIn are the
safer contact channels. If you really want the phone shown, say so and I'll add it.

## Deploy to GitHub Pages

### Recommended: personal site at `capuron.github.io`
Lives at **https://capuron.github.io** (clean URL).

```bash
cd ~/project/capuron-portfolio
git init && git add . && git commit -m "Portfolio site"
git branch -M main
gh repo create capuron.github.io --public --source=. --remote=origin --push
```
Then on GitHub: **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)` → Save.**
Live in ~1 minute.

> The hosting repo is **public**, but it only contains this one HTML file — none of your
> private project source is exposed.

## Custom domain (optional)
Own a domain? Add it under **Settings → Pages → Custom domain** and GitHub writes the `CNAME`.

## Updating later
```bash
git add . && git commit -m "Update portfolio" && git push
```
Pages redeploys automatically.
