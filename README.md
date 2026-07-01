# Renowa Labs

Coming-soon landing page for Renowa Labs, a technology solutions company.

## Deploy (GitHub Pages)

1. Push this repo to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set Source to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Under **Custom domain**, enter `renowa-labs.com` and save (this repo already includes a `CNAME` file with that value).
5. At your domain registrar, point DNS at GitHub Pages:
   - `A` records for `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` record for `www` → `<your-github-username>.github.io`
6. Back in Settings → Pages, enable **Enforce HTTPS** once DNS propagates.
