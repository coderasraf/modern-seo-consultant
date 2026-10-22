# Complete SEO Mastery Roadmap

An interactive, single-page roadmap for going from Shopify developer to professional SEO consultant: every skill to learn, in order, with extra depth on technical, Shopify, ecommerce, international and AI search.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Open-2EA44F?logo=githubpages&logoColor=white)](https://coderasraf.github.io/modern-seo-consultant/) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?logo=githubpages&logoColor=white)

## Overview

A personal study guide built as one self-contained `index.html` file (no build step, no dependencies besides Google Fonts). It maps the SEO field into 12 stages and lets you open any topic for details, learning resources and a ready-made AI study prompt, while tracking which topics you have learned.

## Features

- 12-stage roadmap: SEO Fundamentals, Keyword Research & Search Intent, Competitor & SERP Research, On-Page SEO, Technical SEO, Content SEO & Topical Authority, Shopify & Ecommerce SEO, Link Building & Authority, Local + International SEO, AEO + GEO + AI Search, Analytics & Reporting, and SEO Consulting
- Clickable topic chips that open a detail panel with an explanation, learning resources and an AI study prompt
- Copy-to-clipboard for the study prompts
- "Learned" progress counter saved in the browser with `localStorage`
- Inline diagrams for each stage (how a page reaches the results, crawl depth and site architecture, keyword-to-page mapping, competitor gap analysis)
- Dedicated sections on Shopify architecture, product/collection/theme SEO, the professional SEO toolkit, an audit process and consulting skills
- Light/dark theme that follows the system preference, with a manual toggle
- Keyboard friendly: topics open with Enter/Space, and the arrow keys step to the previous/next topic inside the detail dialog
- Previous/next navigation and a "mark as learned" button in each topic dialog

## Tech Stack

- HTML5, CSS3 and vanilla JavaScript (single file)
- Google Fonts (Archivo, Public Sans)
- GitHub Pages (Jekyll Pages workflow) for hosting

## Getting Started

No build step is needed.

```bash
git clone https://github.com/coderasraf/modern-seo-consultant.git
cd modern-seo-consultant
# open index.html in your browser, or serve it locally:
npx serve .
```

## Project Structure

```text
modern-seo-consultant/
├── index.html                          # The entire roadmap (markup, styles, scripts, content)
└── .github/workflows/jekyll-gh-pages.yml   # Deploys to GitHub Pages on push to main
```

## Live Demo

[coderasraf.github.io/modern-seo-consultant](https://coderasraf.github.io/modern-seo-consultant/)

## Author

Built by **Ashraf Siddik**, Shopify developer & CRO specialist.

- Website: [ashraf-siddik.com](https://ashraf-siddik.com)
- GitHub: [@coderasraf](https://github.com/coderasraf)
