# Design Spec: Aesthetic GitHub Profile (Editorial Typographic Theme)
Date: 2026-07-13
Author: opencode
Target Repository: phowdecayed/phowdecayed

## 1. Overview
The goal of this project is to transform the empty profile repository `phowdecayed/phowdecayed` into a highly aesthetic, modern, and professional GitHub Profile README. The design adopts an **Editorial Typographic (Warm Monochrome)** style, drawing inspiration from minimalist print magazines, high-end galleries, and luxury product presentation sites.

## 2. Visual Style Guidelines
- **Color Palette:** Warm Monochrome. Grayscale accents (`#1E1E1E`, `#555555`, `#EEEEEE`) with transparent backgrounds where appropriate.
- **Typography:** Spacious, elegant layout relying on standard Markdown blockquotes and spacing to mimic publication design.
- **Iconography:** Flat-square minimalist badges with `#1E1E1E` background and white text/logos, avoiding bright/clashing default brand colors.
- **Alignment:** Clean left-aligned structure with elegant thin dividers (`---`) to anchor elements.

## 3. Structure and Layout Sections

### Section 1: Hero & Quote
- **Title:** `Rachmat S. Haryadi` in H1 header.
- **Subtitle:** `Perpetual Learner` in italic formatting.
- **Divider:** Standard horizontal rule (`---`).
- **Quote:**
  > "We all have our time machines, don't we? Those that take us back are memories... and those that carry us forward are dreams."
  > — *Alexander Hartdegen, The Time Machine*
- **Divider:** Standard horizontal rule (`---`).

### Section 2: About Me
- A brief, philosophically-aligned introduction highlighting the core mindset of a lifelong learner:
  > I find joy in the process of turning curiosity into comprehension. As a developer, my journey is defined not by what I already know, but by the relentless pursuit of what is yet to be discovered.

### Section 3: Tech Stack
- Displaying PHP, JS, TS, and Python using customized flat-square badges (`style=flat-square`, `#1E1E1E` background, white logos).
- Code representation:
  ```markdown
  <p align="left">
    <img src="https://img.shields.io/badge/PHP-1E1E1E?style=flat-square&logo=php&logoColor=white" alt="PHP" />
    <img src="https://img.shields.io/badge/JavaScript-1E1E1E?style=flat-square&logo=javascript&logoColor=white" alt="JS" />
    <img src="https://img.shields.io/badge/TypeScript-1E1E1E?style=flat-square&logo=typescript&logoColor=white" alt="TS" />
    <img src="https://img.shields.io/badge/Python-1E1E1E?style=flat-square&logo=python&logoColor=white" alt="Python" />
  </p>
  ```

### Section 4: Current Focus (The Mindset)
- Displaying current learning & exploring targets to match the "Perpetual Learner" narrative:
  - **Deepening:** Advanced software patterns and system architectures.
  - **Exploring:** Modern frontend frameworks and robust backend APIs.
  - **Reading:** Philosophical essays and tech whitepapers.

### Section 5: Monochrome Metrics
- GitHub Stats card with custom query parameters matching the dark-theme/monochrome aesthetic:
  - Transparent background (`bg_color=00000000`)
  - Title color `#1E1E1E`
  - Text color `#555555`
  - No border (`hide_border=true`)
  - Target username: `phowdecayed`
