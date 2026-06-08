# Glyde Games — Legal

Static legal pages (Privacy Policy & Terms of Use) for Glyde Games mobile apps,
hosted on Vercel. Operated by **Glyde Games Oyun ve Yazılım Anonim Şirketi**.

## Structure
```
index.html            landing page (lists all apps)
style.css             shared styles
spot/privacy.html     → /spot/privacy
spot/terms.html       → /spot/terms
vercel.json           cleanUrls routing
```

## Add a new app
1. Create `appname/privacy.html` and `appname/terms.html` (copy from `spot/`).
2. Add the links to `index.html`.
3. Push — Vercel redeploys automatically (or `vercel --prod`).

URLs (cleanUrls): `https://<domain>/<app>/privacy` and `/<app>/terms`.
