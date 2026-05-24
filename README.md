# AI Prompt Architect Pro v3.0

**A Web-Based Tool for Structured AI Prompt Generation in Science Education**

AI Prompt Architect Pro is a client-side web application that helps educators generate structured, pedagogically grounded prompts for creating interactive educational HTML applications with generative AI systems.

The tool follows a guided three-step workflow that combines curriculum content, educational application patterns, UI/UX principles, and accessibility guidance.

## Version

- Version: v3.0
- DOI: https://doi.org/10.5281/zenodo.20368438
- Previous Zenodo version: https://doi.org/10.5281/zenodo.19187956
- Release date: 2026-05-24

## Main Files

The application consists of three HTML modules that must remain in the same folder:

1. `chemistry_curriculum_en.html` - Curriculum selection module
2. `efarmoges_en.html` - Application type selection module
3. `prompt_generator_en.html` - Prompt Studio and generation module

The package also includes:

- `User_Manual_v3.html` - User manual and documentation
- `CITATION.cff` - Machine-readable citation metadata
- `LICENSE` - License statement
- `CHANGELOG.md` - Version notes
- `FILE_MANIFEST.md` - Package file inventory
- `ZENODO_UPLOAD_FIELDS.md` - Suggested Zenodo metadata fields
- `.zenodo.json` - Optional Zenodo/GitHub metadata

## How to Run

No installation or server is required for the core workflow.

1. Download and extract the package.
2. Keep the three HTML application files in the same directory.
3. Open `chemistry_curriculum_en.html` in a modern web browser.
4. Complete the workflow:
   - Step 1: Select curriculum content and learning outcomes.
   - Step 2: Select one or more educational application types.
   - Step 3: Configure design parameters and generate the AI prompt.

## Features

- Hierarchical navigation of Grade 11 Chemistry curriculum content.
- Selection of learning outcomes and suggested pedagogical activities.
- Library of educational application types across core tools, gamification, simulations, virtual labs, and AI-supported learning designs.
- Prompt generation for systems such as ChatGPT, Claude, Gemini, and Copilot.
- Integration of Nielsen's usability heuristics, Norman's design principles, and WCAG 2.1 accessibility guidance.
- Visual style and color palette configuration.
- Optional live execution through a user-supplied Google Gemini API key.

## Technical Notes

- Technology: HTML5, CSS3, vanilla JavaScript.
- Architecture: Static client-side application; no backend or database.
- State transfer: Browser `localStorage` between modules.
- External assets: Google Fonts and Font Awesome are loaded from public CDNs.
- Browser support: Modern versions of Chrome, Firefox, Edge, and Safari.

## Intended Audience

- Science educators.
- Teacher trainers and professional development facilitators.
- Instructional designers.
- Educational technology researchers.
- HCI and UX researchers studying AI-assisted educational design.

## AI Disclosure

The software was developed and refined with assistance from generative AI tools. The author reviewed, edited, tested, and validated the resulting content, code, interface structure, pedagogical mappings, and documentation.

## Author

Georgios Korakakis, PhD  
Assistant Professor  
Department of Graphic Design and Visual Communication  
School of Applied Arts and Culture  
University of West Attica (UNIWA), Greece  

ORCID: https://orcid.org/0009-0005-0042-6348

## Citation

If you use this software in research or teaching, please cite:

```text
Korakakis, G. (2026). AI Prompt Architect Pro v3.0: A Web-Based Tool for Structured
AI Prompt Generation in Science Education [Software]. Zenodo.
https://doi.org/10.5281/zenodo.20368438
```

## License

The software code is released under the MIT License.

The accompanying user manual and documentation are released under the Creative Commons Attribution 4.0 International License (CC BY 4.0).
