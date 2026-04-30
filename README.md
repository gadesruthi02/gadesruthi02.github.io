# Sruthi Gade Portfolio

Personal portfolio site for Sruthi Gade, a Business Data Analyst focused on healthcare analytics, KPI reporting, SQL, Python, Power BI, Tableau, ETL workflows, and stakeholder-ready insights.

## Overview

This is a static, JSON-driven portfolio built with vanilla HTML, CSS, and JavaScript. Content lives in the `data/` directory, so updates to experience, projects, skills, education, and contact details do not require changing the page markup.

## Run Locally

```bash
npm run dev
```

Then open:

```text
http://127.0.0.1:8001
```

The local server is required because the page loads content from `data/*.json` with `fetch()`.

## Project Structure

```text
assets/
  css/styles.css      Site design system and responsive styles
  js/main.js          Data loading, navigation, contact form, and interactions
data/
  *.json              Portfolio content and site configuration
index.html            Static page shell
package.json          Local server scripts and project metadata
```

## Content Updates

- `data/hero.json`: headline, summary, highlights, and primary calls to action
- `data/about.json`: profile copy, metrics, and resume/contact action
- `data/experience.json`: professional experience timeline
- `data/projects.json`: featured analytics and data engineering projects
- `data/skills.json`: technical skill categories
- `data/education.json`: education and certifications
- `data/contact.json`: contact details and form fields
- `data/site-config.json`: SEO metadata and site branding

## Deployment

This repository is ready for GitHub Pages. Push changes to the default branch for `https://gadesruthi02.github.io`.
