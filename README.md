# Paperwork Vault Landing Page

This repository contains the source for a clean, fully responsive landing page for **Paperwork Vault**—a secure document management platform designed for families, entrepreneurs and estates.

## Structure

```
paperwork-site/
├── index.html      # Main HTML document
├── style.css       # Extracted CSS styles
├── assets/         # Static assets (logo, icons, etc.)
│   └── logo.png    # Optional logo file
├── README.md       # Project overview and instructions
└── .gitignore      # Files to ignore in version control
```

## Getting Started

To run the site locally you just need a browser. Clone the repository and open `index.html` in your favourite browser.

```bash
git clone <repo-url>
cd paperwork-site
open index.html   # or use your OS equivalent
```

## Hosting

This is a static site so it can be hosted on any platform that serves HTML/CSS, including:

- **GitHub Pages** – simply push the `paperwork-site` folder to a GitHub repository and enable Pages on the `main` branch. GitHub will automatically serve `index.html` at `https://<your-username>.github.io/<repo-name>/`.
- **Netlify** or **Vercel** – drag and drop the folder or connect your Git repository to deploy.
- **AWS S3 + CloudFront** – upload the files to an S3 bucket and configure a CDN for custom domains.

For GitHub Pages, ensure your repository has a **public** visibility and the Pages source is set to the root (`/`) of the `main` branch. After enabling, allow a few minutes for DNS propagation.

## Customising

- **Logo**: Replace `assets/logo.png` with your own 36×36 logo. The existing HTML uses an inline SVG lock mark, but the placeholder file is there if you wish to use an image instead.
- **Colour palette**: Adjust the CSS variables at the top of `style.css` to change the brand colours.
- **Copy and pricing**: Update the HTML content to match your pricing tiers, testimonials, and CTAs.

## License

This project is provided without a licence. You can adapt and reuse the code for your own projects. Attribution is appreciated but not required.