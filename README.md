# BuildSparks website

## Cloudflare Pages deployment

### Dashboard
1. Sign in to Cloudflare and open Workers & Pages.
2. Create application > Pages > Upload assets.
3. Upload this folder or the ZIP contents.
4. Name the project `buildsparks` and deploy.
5. In Custom domains, add your BuildSparks domain.

### Wrangler CLI
```bash
npx wrangler pages deploy . --project-name=buildsparks
```

No build command is needed. The production asset is `index.html`.
