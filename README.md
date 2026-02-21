# Legal Documents

These HTML files must be hosted and accessible at the URLs configured in `AppConfig.swift`:

- **Privacy Policy:** `https://juhd.app/privacy` (or `/privacy.html`)
- **Terms of Service:** `https://juhd.app/terms` (or `/terms.html`)

## Deployment options

1. **juhd.app** – Upload `privacy.html` and `terms.html` to your web server. Configure routes so `/privacy` and `/terms` serve these files.

2. **GitHub Pages** – Push the `docs` folder to a repo and enable GitHub Pages. URLs would be like `https://yourusername.github.io/juhd/legal/privacy.html`. Update `AppConfig.swift` if using this.

3. **Supabase Storage** – Upload to a public bucket and use the generated URLs.

4. **Vercel / Netlify** – Deploy the `docs` folder as a static site.

After deploying, verify the URLs work in a browser before submitting to App Store Connect.
