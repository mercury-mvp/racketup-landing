# RacketUp landing site

Static public marketing site for `getmercury.mercury-mvp.com`.

GitHub Pages deploys `main` through `.github/workflows/deploy-pages.yml`.
The site deliberately has no runtime API, database, or application credentials.
The contact call to action opens an email to `admin@mercury-mvp.com`.

## Release verification

1. Confirm the GitHub Pages deployment succeeds.
2. Keep the repository custom domain set to `getmercury.mercury-mvp.com`.
3. Point the Squarespace `getmercury` CNAME record to `mercury-mvp.github.io`.
4. Enable HTTPS in GitHub Pages after DNS propagation.
