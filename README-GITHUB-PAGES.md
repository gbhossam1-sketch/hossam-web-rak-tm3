# Zineb Fastfood — GitHub Pages Ready

This is the React + Vite version prepared for deployment to:

https://gbhossam1-sketch.github.io/hossam-web1/

## Important fixes

- GitHub Pages base path is configured as `/hossam-web1/`.
- All website image URLs use Vite's `import.meta.env.BASE_URL`, so images work from the repository subpath.
- `index.html` uses Vite's `%BASE_URL%` placeholder for public assets.
- GitHub Actions deployment is included at `.github/workflows/deploy.yml`.
- The original React/Vite structure and visual design are preserved.

## Deploy

1. Upload/replace the project files in the `hossam-web1` repository.
2. In GitHub: Settings → Pages → Source → **GitHub Actions**.
3. Push the project to the `main` branch.
4. Open the Actions tab and wait for the deployment workflow to finish.
