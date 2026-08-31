# Deploy this Hydejack site to GitHub Pages

1. Create a new GitHub repository. Use `<username>.github.io` if you want the site at `https://<username>.github.io/`; otherwise choose any repository name.
2. Upload/push the **contents of this folder** to the repository's `main` branch. Do not upload the outer ZIP folder as one file.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **GitHub Actions**.
5. Open the **Actions** tab and wait for the workflow named **Deploy Jekyll site to Pages** to complete successfully.
6. The deployment job will show the public site URL.

## Git commands

From this folder:

```bash
git init
git add .
git commit -m "Deploy Hydejack site"
git branch -M main
git remote add origin https://github.com/<YOUR_USERNAME>/<YOUR_REPOSITORY>.git
git push -u origin main
```

## Personalize before publishing

Edit `_config.yml` and replace at least:

- `title`
- `description`
- `tagline`
- `author.name`
- `author.email`
- `copyright`
- sidebar/menu links if needed

GitHub Actions supplies the correct Pages base path automatically, so `url` and `baseurl` can stay commented out for this workflow.
