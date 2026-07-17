# First English Lutheran Church

Modern redesign of **[felconline.org](https://www.felconline.org/)** — First English Lutheran Church, Richmond, Indiana.

**Local folder:** `C:\Users\dexte\first-english-lutheran`  
**GitHub:** https://github.com/dextermelling-design/first-english-lutheran

## Content source

Public content adapted from the current SnapPages site at felconline.org:

- Address, phone, and Sunday schedule  
- Motto: *Reaching, Growing, Loving*  
- History (1884 → present)  
- Beliefs & ELCA affiliation  
- Staff directory  
- Growing Deeper / get involved ministries  

## Pages

| Page | File |
|------|------|
| Home | `index.html` |
| Our Story | `about.html` |
| Beliefs | `beliefs.html` |
| Worship | `worship.html` |
| Get Involved | `ministries.html` |
| Staff | `staff.html` |
| Contact | `contact.html` |

## Preview

```powershell
start C:\Users\dexte\first-english-lutheran\index.html
```

## Deploy (Netlify)

1. [app.netlify.com](https://app.netlify.com) → **Add new site** → import **`first-english-lutheran`**
2. Branch `main` · build empty · publish `.`
3. Later: point **felconline.org** DNS to this Netlify site when ready to replace the old site

## Push updates

```powershell
cd C:\Users\dexte\first-english-lutheran
git add .
git commit -m "Describe change"
git push
```
