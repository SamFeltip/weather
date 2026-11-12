# Weather app

GitHub Actions deploys the site to the `weather` Cloudflare Pages project on
pushes to `main`. The workflow can also be run manually from `main`.

The repository needs two Actions secrets:

- `CLOUDFLARE_ACCOUNT_ID` for the Cloudflare account that owns the project.
- `CLOUDFLARE_API_TOKEN` with Account → Cloudflare Pages → Edit permission
  for that account.
