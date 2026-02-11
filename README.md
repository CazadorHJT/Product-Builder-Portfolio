# Hunter Thomas — Product Builder Portfolio

A professional portfolio website built with [Quarto](https://quarto.org/) and automatically deployed to GitHub Pages. Showcases projects in product management, software engineering, and automotive technology.

## Live Site

**https://cazadorhjt.github.io/Product-Builder-Portfolio/**

## Projects

| Project | Description | Links |
|---------|-------------|-------|
| **SwapSpec** | AI-driven engine swap planning platform built with FastAPI, Supabase, Unity, and Claude AI | [Details](https://cazadorhjt.github.io/Product-Builder-Portfolio/projects/project-1.html) · [Source](https://github.com/CazadorHJT/SwapSpec) |
| **Pixel Maze Game** | Browser-based maze game with procedurally generated levels, built with Next.js, React, and TypeScript | [Details](https://cazadorhjt.github.io/Product-Builder-Portfolio/projects/project-2.html) · [Play](https://pixel-maze-game.vercel.app) · [Source](https://github.com/CazadorHJT/pixel-maze-game) |
| **MCAT Prep App** | Adaptive MCAT study platform with 3,790 questions across 7 subjects, built with React, FastAPI, and Supabase | [Details](https://cazadorhjt.github.io/Product-Builder-Portfolio/projects/project-3.html) · [Try](https://mcat-prep-app.vercel.app) · [Source](https://github.com/CazadorHJT/MCAT-Prep-App) |

## Tech Stack

- **Static Site Generator:** Quarto with Bootstrap "cosmo" theme
- **Styling:** Custom CSS + Font Awesome icons
- **Deployment:** GitHub Pages via GitHub Actions (auto-deploys on push to `main`)

## File Structure

```
├── _quarto.yml                      # Website configuration (nav, theme, metadata)
├── index.qmd                        # Homepage with featured projects
├── about.qmd                        # Background, skills, education, career goals
├── styles.css                       # Custom styling
├── projects/
│   ├── project-1.qmd               # SwapSpec
│   ├── project-2.qmd               # Pixel Maze Game
│   └── project-3–6.qmd             # Placeholders for future projects
├── images/
│   └── profile.jpg                  # Profile photo
└── .github/workflows/publish.yml    # CI/CD deployment workflow
```

## Local Development

1. Install [Quarto](https://quarto.org/docs/get-started/)
2. Run `quarto preview` from the project root
3. The site will open in your browser and auto-refresh on file changes
