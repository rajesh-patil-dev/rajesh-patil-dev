# How to publish this profile README

GitHub shows a special repository's `README.md` at the top of your profile page.
That repository must be **named exactly like your GitHub username**.

## 1. Replace the placeholders

Edit `README.md` and replace:

| Placeholder | Replace with |
| --- | --- |
| `YOUR_GITHUB_USERNAME` | your exact GitHub username (appears in the stats/badge/counter URLs) |
| `YOUR_LINKEDIN_HANDLE` | your LinkedIn vanity handle, or delete the LinkedIn badge line |
| `YOUR_PORTFOLIO_URL` | your portfolio/site URL, or delete the Portfolio badge line |

## 2. Create the repo on GitHub

- Go to https://github.com/new
- **Repository name:** your username (e.g. if you are `octocat`, name it `octocat`)
- Visibility: **Public**
- Do **not** add a README from the form (this folder already has one)

## 3. Push this folder

```bash
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME.git
git branch -M main
git push -u origin main
```

## 4. Check it

Open `https://github.com/YOUR_GITHUB_USERNAME` — the README renders on your profile.

## Notes

- The stats widgets (`github-readme-stats`, `github-readme-streak-stats`) and the
  `komarev` view counter are third-party image services. They render as images
  only; nothing runs in your repo.
- No personal contact details (phone, email, street address) are included by design.
