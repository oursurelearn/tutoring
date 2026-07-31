# OursureLearn

Static website for [oursurelearn.com](https://oursurelearn.com) — tutor listings starting with Math (Sarat Sahoo).

## Local preview

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deploy with GitHub Pages

1. Create a GitHub repo (e.g. `oursurelearn`) and push this folder.
2. In the repo: **Settings → Pages**.
3. Set source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. After the first deploy, add your custom domain `oursurelearn.com` (this repo already includes a `CNAME` file).
5. At your domain registrar, add DNS records as GitHub Pages instructs (usually `A` records or a `CNAME` for `www`).

Contact email on the site: `oursurelearn@gmail.com`.
