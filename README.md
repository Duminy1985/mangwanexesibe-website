MangwaneXesibe Corporate Solutions - Starter Site (Netlify-ready)
----------------------------------------------------------------

This project is pre-configured for deployment to Netlify and is set up for the domain **mangwanexesibe.co.za**.

Files of interest:
- netlify.toml  (Netlify build settings + redirect)
- public/site.webmanifest  (PWA manifest)
- public/*.png, favicon.ico (logo & favicons)
- src/App.jsx, src/main.jsx

Quick deploy (recommended: GitHub → Netlify)
1. Create a GitHub repo and push this project.
2. On Netlify: New Site -> Import from Git -> select repo.
   Build command: npm run build
   Publish directory: dist
3. After deploy, in Netlify dashboard -> Domain management -> Add custom domain -> mangwanexesibe.co.za
   Follow Netlify's DNS instructions (add the CNAME for www and A/ALIAS for the root domain at your registrar).
4. Netlify will provision SSL (HTTPS) automatically.

Local preview:
- npm install
- npm run dev

Netlify Forms:
- The contact form is wired for Netlify Forms (data-netlify="true"). Keep the site deployed from Git for Netlify Forms to be detected.

