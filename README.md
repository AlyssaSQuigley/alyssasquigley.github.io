# Alyssa Q. | Personal Portfolio Website

Personal portfolio website built with Quarto and hosted on GitHub Pages. Built for AD 688 Big Data & Cloud Analytics for Business (Boston University MS in Applied Business Analytics).

**Live site:** https://alyssasquigley.github.io

## Pages

| Page | File | What it covers |
|---|---|---|
| About | index.qmd | Background, my view on procurement and analytics, career goals and community leadership |
| Projects | projects.qmd | Six projects with visuals and details, plus a supplier cost calculator |
| CV | cv.qmd | Career timeline, education, coursework and a downloadable PDF |
| Contact | contact.qmd | Email, LinkedIn and GitHub |

## Project structure

```
_quarto.yml          Site settings (navigation, theme, footer)
styles.css           Colors, fonts and layout
pizazz.html          Number count-ups and scroll effects
motion.html          Typing effect on the home page
images/              Headshot, favicon and project images
files/               CV PDF
.github/workflows/   Publishes the site on every push
```

## How the site is published

Pushing to `main` runs a GitHub Actions workflow. It renders the site and publishes it to the `gh-pages` branch, which GitHub Pages serves.
