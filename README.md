# Significo Clone

A pixel-perfect static clone of the **Significo** website[](https://www.significo.com/), built with pure HTML, CSS, and JavaScript.

This project replicates the clean, modern design and layout of Significo's homepage — a healthcare technology company focused on human-centric software, AI, digital health tools, and patient-first experiences.

Deployed as a static site on **AWS S3** with automated CI/CD via **AWS CodePipeline** + GitHub integration.

## Live Demo

🔗 https://significo-clone.s3.eu-north-1.amazonaws.com/index.html

## Features

- Smooth scrolling and interactive elements
- Clean typography and modern color scheme
- Section-based layout mirroring the original site:
  - Hero section
  - Mission & values
  - Services / Solutions
  - Testimonials / Stats
  - Footer with links
- No external frameworks — 100% vanilla HTML/CSS/JS

## 🛠️ Tech Stack

- **HTML5**
- **CSS3** (custom styles, flexbox, grid, animations)
- **JavaScript** (vanilla — for interactivity & smooth behavior)
- **AWS S3** → Static website hosting
- **AWS CodePipeline** → Automated CI/CD from GitHub
- **GitHub** → Source control & trigger pipeline on push

## Deployment Workflow

1. Code committed & pushed to `main` branch on GitHub
2. GitHub webhook triggers AWS CodePipeline
3. Pipeline pulls latest code
4. Builds (static files — no build step needed)
5. Deploys directly to S3 bucket
6. CloudFront (optional) invalidation for instant updates

This setup enables **zero-downtime, fully automated deployments** for static sites — great for learning modern cloud hosting & DevOps practices.

## Project Structure
**Project files:**

- `index.html`       → The main landing page (HTML structure of the Significo clone)  
- `style.css`        → All visual styling, including layout (flex/grid), colors, typography and animations  
- `script.js`        → Client-side JavaScript for menu toggles, smooth scrolling, and other small interactions  
- `README.md`        → Project documentation with setup instructions, deployment info and purpose  
- `LICENSE`          → MIT License – legal terms for using/distributing the project  
