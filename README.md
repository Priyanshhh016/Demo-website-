# Priyansh Sharma — Robotics & AI portfolio

A complete static portfolio ready for Vercel. Includes responsive layouts, project search, status filtering, project detail dialogs, and section navigation. No framework, build process, API key, database, or Sites account is needed to run this copy.

## Deploy with GitHub and Vercel (recommended for future upgrades)

1. Extract this ZIP.
2. Create a GitHub repository, for example priyansh-portfolio.
3. Upload the contents of this folder to the repository. public/ and vercel.json must be at the repository root; do not upload the ZIP itself.
4. Sign in at https://vercel.com and choose Add New → Project.
5. Import the GitHub repository.
6. Use Framework Preset: Other. Root Directory: repository root. Output Directory: public. Leave Build Command empty. The included vercel.json already sets the framework and output settings.
7. Click Deploy. Vercel will give you the actual website URL. Open that URL and check whether visitors can access it without signing in; adjust deployment protection if it is enabled.

Future changes pushed to the connected production branch can be deployed by the Git integration.

## Alternative: deploy from your computer

With Node.js installed, open a terminal in the extracted folder containing vercel.json and run:

    npx vercel@latest --prod

Sign in and follow the setup prompts. Use the settings above if asked. The command returns your deployed URL.

## Preview and upgrade

Open public/index.html in a browser to preview the current site.

- public/index.html: name, education, introduction, navigation, and internship availability.
- public/style.css: colors, typography, layout, responsive breakpoints.
- public/app.js: project descriptions, technologies, statuses, search, filters, and dialogs.

Add your real email, LinkedIn, résumé, and project photos when ready. The current copy deliberately does not invent them, results, or achievements. Keep the surveillance mesh marked in progress until its status changes.

This package is independent of the existing private Sites deployment. No existing Sites credentials or hosting metadata are included.

A Vercel URL is enough for a public portfolio. A personal domain is optional and can be connected later through Vercel Project Settings → Domains. A domain does not need to be purchased to deploy this site.

Official deployment documentation:
https://vercel.com/docs/deployments
https://vercel.com/docs/builds/configure-a-build
https://vercel.com/docs/cli/deploy
