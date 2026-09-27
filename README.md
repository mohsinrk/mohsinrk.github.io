# mohsinkhan.bio

Personal website of Mohsin Khan, Ph.D. Static HTML hosted on GitHub Pages.

## Deploy
1. Upload all files in this folder (including `CNAME` and `.nojekyll`) to the root of a GitHub repository.
2. Repository **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
3. Custom domain `mohsinkhan.bio` is set via the `CNAME` file. At your DNS provider (e.g. Porkbun), add:
   - `A` records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME` for `www` → `<your-github-username>.github.io`
4. Once DNS resolves, tick **Enforce HTTPS** in Settings → Pages.
