# First English Lutheran Church

Independent website (Option A: own folder, GitHub repo, and Netlify site).

## Local

```
C:\Users\dexte\first-english-lutheran
```

Preview:

```powershell
start C:\Users\dexte\first-english-lutheran\index.html
```

## Pages

| Page | File |
|------|------|
| Home | `index.html` |
| About | `about.html` |
| Worship | `worship.html` |
| Ministries | `ministries.html` |
| Contact | `contact.html` |

## Placeholders to customize

- Address, phone, email
- Worship / office hours
- Pastor name and history
- Denomination / affiliation
- Map embed on Contact

## Pipeline

```
Edit → git commit → git push → GitHub → Netlify auto-deploy
```

### Connect Netlify (one-time)

1. [app.netlify.com](https://app.netlify.com) → **Add new site** → **Import an existing project**
2. Choose **GitHub** → repo **`first-english-lutheran`**
3. Branch: `main` · Build command: *(empty)* · Publish directory: `.`
4. Deploy — you’ll get a new `*.netlify.app` URL

## Day-to-day

```powershell
cd C:\Users\dexte\first-english-lutheran
git add .
git commit -m "Update site content"
git push
```
