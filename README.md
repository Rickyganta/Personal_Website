# Personal Website - Ricky Johnson Ganta

A clean, professional personal website showcasing my experience as an ML / AI Engineer and Data Scientist.

## Features

- **Clean & Professional Design**: Simple, recruiter-friendly layout optimized for job applications
- **Mobile Responsive**: Works seamlessly on all devices
- **Fast Loading**: Lightweight with no heavy dependencies
- **ATS-Friendly**: Semantic HTML structure for better parsing
- **Auto-Deployment**: GitHub Actions automatically deploys to GitHub Pages

## Tech Stack

- HTML5
- CSS3 (Vanilla)
- JavaScript (Vanilla)
- GitHub Pages (Hosting)
- GitHub Actions (CI/CD)

## Project Structure

```
My website/
├── index.html              # Main landing page
├── assets/
│   ├── css/
│   │   └── style.css      # All styling
│   └── js/
│       └── main.js        # Interactive features
├── resume/
│   └── resume.pdf         # Resume PDF (add your file here)
├── .github/
│   └── workflows/
│       └── deploy.yml     # GitHub Actions workflow
└── README.md              # This file
```

## Setup Instructions

1. **Clone or download this repository**

2. **Add your resume PDF**
   - Place your resume PDF file in the `resume/` directory
   - Name it `resume.pdf`

3. **Update project information**
   - Edit `index.html` to add your actual projects
   - Update project titles, descriptions, and GitHub links
   - Remove placeholder project cards or replace with real ones

4. **Deploy to GitHub Pages**
   - Push this repository to GitHub
   - Go to Settings → Pages in your GitHub repository
   - Select source: "GitHub Actions"
   - The workflow will automatically deploy on every push to main/master

## Customization

### Update Projects
Edit the project cards in `index.html` (lines ~60-100):
- Replace "Project Title" with your actual project names
- Update descriptions
- Add correct GitHub repository links
- Update technology tags

### Update Colors
Edit CSS variables in `assets/css/style.css` (lines ~8-15):
- `--primary-color`: Main brand color
- `--text-primary`: Main text color
- `--bg-primary`: Background color

### Add Profile Photo
1. Add your photo to `assets/images/`
2. Update the hero section in `index.html` to include an `<img>` tag

## License

This project is open source and available for personal use.
