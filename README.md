# Ice Portfolio

A personal portfolio website with the following pages and structure.

## Site Pages

- **Home** – `index.html` (hero, intro, highlights)
- **Projects** – `pages/projects/projects.html` (grid of 6 project cards)
- **About Me** – `pages/about.html`
- **Contact** – `pages/contact.html`

## Project Detail Pages

Each project has its own detail page under `pages/projects/`:
- `project-1.html`
- `project-2.html`
- `project-3.html`
- `project-4.html`
- `project-5.html`
- `project-6.html`

## Folder Structure

```
Ice-Portfolio/
├── index.html                        # Home page
├── README.md                         # This file
├── pages/
│   ├── about.html                    # About Me page
│   ├── contact.html                  # Contact page
│   └── projects/
│       ├── projects.html             # Projects listing (6 cards)
│       ├── project-1.html            # Project 1 detail
│       ├── project-2.html            # Project 2 detail
│       ├── project-3.html            # Project 3 detail
│       ├── project-4.html            # Project 4 detail
│       ├── project-5.html            # Project 5 detail
│       └── project-6.html            # Project 6 detail
├── assets/
│   ├── css/
│   │   └── style.css                 # Main stylesheet
│   ├── js/
│   │   └── main.js                   # Main JavaScript
│   └── images/
│       ├── hero/                     # Hero/banner images
│       ├── about/                    # About section images
│       └── projects/                 # Project images
│           ├── project-1/
│           ├── project-2/
│           ├── project-3/
│           ├── project-4/
│           ├── project-5/
│           └── project-6/
```

## Image Naming Convention

- Hero images: `assets/images/hero/hero-bg.jpg`, `hero-profile.jpg`
- About images: `assets/images/about/about-photo.jpg`
- Project thumbnails: `assets/images/projects/project-N/thumbnail.jpg`
- Project detail images: `assets/images/projects/project-N/detail-1.jpg`, `detail-2.jpg`, etc.

## Notes for Claude

- All pages share the same nav (Home, Projects, About, Contact)
- CSS variables and shared styles are in `assets/css/style.css`
- JavaScript for interactivity is in `assets/js/main.js`
- Image paths are relative from each HTML file's location
- From `pages/`: use `../assets/images/...`
- From `pages/projects/`: use `../../assets/images/...`
- From root `index.html`: use `assets/images/...`
