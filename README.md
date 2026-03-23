# AI Prompt Architect Pro

AI Prompt Architect Pro is a web-based authoring environment for designing interactive educational applications through AI-driven prompt engineering.

The system combines curriculum-aligned learning outcomes, application design patterns, and human-centered design principles to help educators, instructional designers, and researchers produce structured prompts for generative AI systems.

## Overview

The application follows a 3-step workflow:

1. **Curriculum Selection** (`index.html`)
2. **Application Type Selection** (`efarmoges_en.html`)
3. **Prompt Generation** (`prompt_generator_en.html`)

Selections are stored in the browser with `localStorage`, so the workflow can move across the three pages without a backend.

## Features

- Curriculum-based chemistry content selection
- Learning-outcome selection with optional suggested activities
- Multiple educational app patterns, including:
  - simulations and virtual labs
  - quizzes and gamified activities
  - flashcards, glossary, calculator, and other learning tools
- Prompt generation for AI tools such as ChatGPT, Gemini, Claude, and Copilot
- Integration of:
  - Nielsen’s usability heuristics
  - Norman’s design principles
  - WCAG 2.1 accessibility guidance
- Design style and color palette options

## Repository Structure

```text
.
├── index.html
├── efarmoges_en.html
├── prompt_generator_en.html
└── README.md
```

## How to Run

### Option 1: Run locally

Since this project is a static HTML/CSS/JavaScript application, you can run it directly in a browser:

1. Download or clone the repository.
2. Open `index.html` in your browser.
3. Continue through the 3-step workflow.

### Option 2: Publish with GitHub Pages

1. Upload the files to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch (usually `main`) and folder `/ (root)`.
5. Save and wait for the site URL to be generated.

## Important Notes

- The current interface loads **Google Fonts** and **Font Awesome** from external CDNs, so it is not fully offline.
- The Prompt Studio includes optional live execution through the **Gemini API**. If you use that feature in a public deployment, users enter their own API key in the browser. Review this carefully before public release.
- No backend or database is required for the core 3-step flow.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Browser `localStorage`

## Intended Audience

- Educators
- Instructional designers
- HCI / UX researchers
- Researchers exploring AI-assisted educational design

## Scientific Background

The system draws on the following foundations:

- Nielsen, J. (1994). *Usability Engineering*
- Norman, D. A. (2013). *The Design of Everyday Things*
- W3C. (2018). *Web Content Accessibility Guidelines (WCAG) 2.1*

## Recommended Repository Extras

For a stronger GitHub repository, consider adding:

- `LICENSE`
- screenshots or a demo GIF
- `CITATION.cff`
- a live GitHub Pages link
- version / release notes

## Author

**Georgios Korakakis**  
Assistant Professor  
Department of Graphic Design and Visual Communication  
University of West Attica

## Citation

If you use this software in academic work, you can cite it as:

> Korakakis, G. (2026). *AI Prompt Architect Pro*.

If a Zenodo DOI is created later, replace the citation above with the final DOI-based citation.
