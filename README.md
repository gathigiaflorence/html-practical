# html-practical

This project demonstrates modern HTML5 features — focusing on semantics, media elements, tables, and accessibility — within the context of sports physiotherapy.  
It helps learners understand how HTML5 can present information about athlete care, rehabilitation, and sports injury tracking.

## 📄 Pages Overview

- **index.html** — Introduces sports physiotherapy with semantic structure, skip links for accessibility, headings, `<blockquote>`, `<time>`, `<abbr>`, and inline code examples (`<code>`, `<kbd>`, `<samp>`).  
- **about.html** — Explains the history of sports physiotherapy in Kenya, lists goals for athlete recovery, and uses `<section>`, lists, and a `<dl>` to define key terms like rehabilitation and preventive therapy.  
- **media.html** — Includes a responsive `<picture>` image of physiotherapy practice, `<audio>` tips for post-match recovery, and a `<video>` with WebVTT captions showing guided exercises.  
- **extras.html** — Demonstrates a weekly physiotherapy training plan in a table (`<caption>/<thead>/<tbody>/<tfoot>`), `<details>` for quick knowledge checks, `<dialog>` for alerts or reminders, and progress indicators (`<progress>`, `<meter>`) to show athlete recovery progress.

## 🌐 Live Demo
The site ia at, https://gathigiaflorence.github.io/html-practical/

## 🎨 Design Decisions

- **Color palette:** Neutral whites and greys for readability, accent color `#0077cc` for links and highlights.  
- **Typography:** System sans-serif stack for body, monospace for code elements. Clear type scale: H1 = 2rem, H2 = 1.5rem, Body = 1rem.  
- **Spacing scale:** `--space-1` 0.5rem → `--space-5` 3rem. Consistent vertical rhythm maintained.  
- **Components:**  
  - `.card` used for home page sections to group content visually.  
  - Tables striped for readability with responsive overflow.  
  - Media elements styled to scale responsively with captions visible.  

## ♿ Accessibility

- Skip link visible on focus.  
- Headings structured hierarchically.  
- Focus outlines clear on links, buttons, and interactive elements.  
- Inline elements (`code`, `kbd`, `samp`, `mark`, `abbr`) visually distinct.  
- Reduced motion respected for users who prefer it.

## 🐳 Docker Setup

Docker Commands
- docker build -t wambuiflorence/html5-css3-site:lab2
- docker login
- docker push wambuiflorence/html5-css3-site:lab2
- docker tag wambuiflorence/html5-css3-site:lab2 wambuiflorence/html5-css3-site:latest
- docker push wambuiflorence/html5-css3-site:latest




