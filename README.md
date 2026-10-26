# Contactly — Ready-made Contact Manager

A responsive contact manager website built with plain HTML, CSS and JavaScript. It does not require Node.js, a backend, a database server, or a build step.

## Features
- Add, edit and delete contacts
- Search contacts
- Filter by Work, Friends, Family and Favorites
- List and card/grid views
- Browser-local saving with localStorage
- Responsive desktop and mobile layout

## Run locally
Open `index.html` in your browser.

## Deploy to Vercel
1. Create a new GitHub repository (for example, `contactly-ready-made`).
2. Upload `index.html` and `README.md` to the repository root.
3. In Vercel, choose **Add New → Project** and import that repository.
4. Select **Other** as the framework if asked.
5. Leave the Build Command empty and use the project root as the output/root directory, then deploy.
6. Open the deployment URL.

## Important storage note
Contacts are saved in the browser on the device and browser profile where they were added. They do not automatically sync between devices or browsers. This static version does not use the old Express/SQL.js backend, so it avoids the serverless function issue in the previous project.
