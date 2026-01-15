# Personal Website

My professional portfolio website showcasing my work as an ML / AI Engineer and Data Scientist. Built with a focus on clarity and performance.

## Overview

This is a clean, minimal personal website designed to highlight my technical expertise, projects, and professional background. The site is optimized for recruiters and hiring managers, with fast load times and a mobile-responsive design.

## Design Philosophy

I designed this website with the following principles in mind:

- **Simplicity**: Clean, uncluttered interface that puts content first
- **Performance**: Lightweight vanilla HTML/CSS/JS for fast loading
- **Accessibility**: Semantic HTML structure for better parsing
- **Responsiveness**: Mobile-first design that works on all devices
- **Professionalism**: Recruiter-focused layout without unnecessary animations

## Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Hosting**: GitHub Pages
- **CI/CD**: GitHub Actions for automatic deployment
- **Fonts**: Inter (Google Fonts)

## Architecture

The site follows a simple, maintainable structure:

```
├── index.html              # Single-page application
├── assets/
│   ├── css/style.css      # Modular CSS with CSS variables
│   └── js/main.js         # Smooth scrolling and navigation
├── resume/
│   └── resume.pdf         # Downloadable resume
└── .github/workflows/
    └── deploy.yml         # Automated deployment pipeline
```

## Features

- **Hero Section**: Clear introduction with name, role, and call-to-action
- **About Section**: Career-focused background and expertise
- **Projects Section**: Showcase of key ML/AI projects with GitHub links
- **Skills Section**: Technical stack organized by category
- **Resume Download**: Direct PDF download link
- **Contact Section**: Email, LinkedIn, and GitHub links
- **Smooth Navigation**: Sticky navbar with active section highlighting

## Deployment

The site is automatically deployed to GitHub Pages via GitHub Actions on every push to the `main` branch. The deployment workflow is configured in `.github/workflows/deploy.yml`.

**Live Site**: [rickyganta.github.io/Personal_Website](https://rickyganta.github.io/Personal_Website)

## Customization

The design uses CSS variables for easy theming. Key variables are defined in `assets/css/style.css`:

- `--primary-color`: Brand color (currently blue)
- `--text-primary`: Main text color
- `--bg-primary`: Background color
- `--max-width`: Content width constraint

## Browser Support

Tested and optimized for:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

Personal use only. All rights reserved.
