# NexaTech Solutions — Website Portfolio

A responsive, multi-page technology website designed as a portfolio/demo aligned with a **WordPress Web Developer Intern** role. It showcases modern web design principles and WordPress-relevant capabilities: Elementor and Gutenberg page building, theme and child-theme customization concepts, responsive layouts, plugin awareness, troubleshooting, SEO foundations, and performance-minded implementation.

> **Portfolio transparency:** The sample project cards and business copy are demo concepts, not claims of paid client work. Replace them with verified project screenshots, links, and your own implementation notes as you complete each build.

## Pages

- `index.html` — homepage, service overview, workflow, featured demo projects
- `wordpress.html` — Elementor, Gutenberg, themes, child themes, plugins, SEO and performance
- `services.html` — website and WordPress service descriptions
- `projects.html` — concept portfolio briefs mapped to the role
- `about.html` — approach and working principles
- `contact.html` — project brief form
- `404.html` — custom not-found page

## Features

- Responsive desktop, tablet, and mobile layouts
- Mobile navigation with keyboard-accessible controls
- Premium dark navy / blue / cyan visual system
- Reusable cards, buttons, page headers, footer, and process sections
- Semantic HTML, skip link, visible focus styles, and reduced-motion support
- Page-specific titles and meta descriptions
- SVG favicon and illustration assets
- No build tools, package manager, or JavaScript framework required

## Run locally

You can open `index.html` directly in a browser. For a local web server (recommended), run this command from the project folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish on GitHub Pages

GitHub Pages serves static files (HTML, CSS, JavaScript, images). This project is built for that hosting model and does not need a build step.

1. Sign in to GitHub and create a new **public** repository, for example `nexatech-solutions-website`.
2. Extract this package on your computer.
3. Open the extracted `NexaTech_GitHub_Website` folder.
4. Upload the **contents of this folder** to the repository root. `index.html` must be at the root, not inside another nested folder.
5. Commit the files to the `main` branch.
6. In the repository, open **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Choose branch `main` and folder `/ (root)`, then click **Save**.
9. Wait for the GitHub Pages deployment to finish. Your website URL will be shown in Settings → Pages. For a project repository it usually looks like `https://YOUR-USERNAME.github.io/nexatech-solutions-website/`.

### Important: update the sitemap and contact email

Before publishing, search the files for these placeholders:

- `YOUR-GITHUB-USERNAME` and `YOUR-REPOSITORY` in `sitemap.xml` and `robots.txt` — replace them with your GitHub username and repository name.
- `YOUR_EMAIL@example.com` in `contact.html` — replace it with the email address where you want to receive enquiries.

The contact form is a **static mailto-based form**. On submit, it prepares an email in the visitor's default email application. It does not send or store messages on a server. For a hosted form endpoint, connect a service such as Formspree and follow that provider's current setup instructions.

## WordPress vs GitHub Pages — hosting note

GitHub Pages cannot run WordPress, PHP, plugins, a WordPress database, or WPForms. It only hosts static files. This repository is a live, GitHub Pages-compatible portfolio website demonstrating the front-end and WordPress workflow concepts described on the WordPress page.

Your separate LocalWP WordPress build can continue to be developed locally. To make that actual WordPress site live with WordPress admin, Elementor, PHP, plugins, and WPForms, deploy it to a WordPress-capable host with PHP and a database (or a managed WordPress provider). Do not upload a LocalWP installation folder to GitHub Pages expecting WordPress to run.

## Suggested next improvements

- Replace sample concept project cards with screenshots and links to your actual WordPress builds.
- Add a live demo URL and repository link for each completed project.
- Connect the contact form to a hosted form service if you want server-side submissions.
- Add a custom domain and update canonical URLs/sitemap if you use one.
- Test the deployed site on phone, tablet, and desktop after publishing.

## Technology

HTML5 · CSS3 · Vanilla JavaScript · SVG · GitHub Pages
