# Guys Hill Landscaping Inc. — Website

A modern, responsive, production-ready website for **Guys Hill Landscaping Inc.**, a professional landscaping company based in Calgary, Alberta, Canada.

## Project Structure

```
website/
├── index.html          # Home page
├── about.html          # About the company
├── services.html       # Detailed services listing
├── portfolio.html      # Project gallery with filtering
├── contact.html        # Contact form, map, and info
├── css/
│   └── styles.css      # Central stylesheet
├── js/
│   └── script.js       # JavaScript for interactivity
├── images/             # Placeholder for local images
└── README.md           # This file
```

## Features

- **Responsive Design** — Works on all devices (mobile, tablet, desktop)
- **Mobile Navigation** — Hamburger menu for small screens
- **Scroll Animations** — Fade-in reveal effects using IntersectionObserver
- **Testimonial Carousel** — Auto-rotating customer reviews
- **Portfolio Filtering** — Filter projects by category
- **Contact Form** — Client-side validation with success feedback
- **Google Maps** — Embedded map showing Calgary location
- **SEO Optimized** — Meta tags, semantic HTML, proper heading hierarchy

## Technologies

- HTML5 (semantic markup)
- CSS3 (custom properties, grid, flexbox, animations)
- Vanilla JavaScript (no frameworks or dependencies)
- Google Fonts (Playfair Display + Inter)

## How to Deploy

### Option 1: Deploy on Netlify

1. Push this folder to a GitHub repository
2. Go to [netlify.com](https://netlify.com) and sign in
3. Click **"Add new site"** → **"Import an existing project"**
4. Connect your GitHub repo
5. Set the **publish directory** to `/website` (or `/` if the repo root is the website folder)
6. Click **Deploy site**

Your site will be live at a Netlify URL. You can add a custom domain in Site Settings.

### Option 2: Host via GitHub Pages

1. Push this folder to a GitHub repository
2. Go to **Settings** → **Pages**
3. Under **Source**, select **main** branch and `/` (root) folder
4. Click **Save**
5. Your site will be live at `https://<username>.github.io/<repo-name>/`

### Option 3: Any Static Host

Simply upload the contents of this folder to any static web hosting service (Vercel, Cloudflare Pages, AWS S3, etc.). No build step is required.

## Images

The website currently uses Unsplash placeholder images via URLs. For production, replace these with your own photos:

1. Add your images to the `images/` folder
2. Update the `src` attributes in the HTML files to point to your local images (e.g., `src="images/hero.jpg"`)

## Contact

- **Phone:** +1 403-217-9112
- **Location:** Calgary, Alberta, Canada
