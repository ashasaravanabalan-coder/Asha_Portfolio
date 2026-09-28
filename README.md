# Asha S. | AI & Data Science Developer: Portfolio

A responsive, dark-themed personal portfolio with a light mode toggle, subtle cursor interactions and scroll animations.

**Stack:** HTML, Tailwind CSS (CDN), vanilla JavaScript. Everything is in one file: `portfolio.html` (photo included).

## Run locally

Double-click `portfolio.html`, or serve the folder:

```bash
npx serve .
```

## Customise

Search `portfolio.html` for these and replace them:

| What | Where to look |
|------|---------------|
| Resume PDF link | `data-placeholder="Replace with your hosted resume PDF URL"` (hero and resume section) |
| Project GitHub / Live Demo links | `data-placeholder="Replace with repo URL"` / `"...live demo URL"` |
| Project text and tech tags | the `const P=[...]` array in the script |
| Skills | the `const skills={...}` object |
| Certifications / achievements | the `#certGrid` and `#achGrid` lists in the script |
| Education | the `#education` section |
| Photo | the `<img src="data:image/jpeg;base64,...">` in the hero |
| Contact email | `sahsa628617@gmail.com` (contact form and footer) |

Please confirm the achievements and skills that came from the brief rather than the resume (IEEE GSEACT 2026, technical-event 1st prize, hackathon, HackWithInfy 2026, Java, C, NLP, LLMs, AWS, FastAPI) before sharing.

## Features

- Dark/light theme toggle and mobile navigation menu
- Project filtering by technology
- Custom cursor, hero glow, 3D card tilt and hover effects (mouse devices only)
- Scroll-reveal animations; all animation is disabled when "reduce motion" is on
- Accessible: skip link, focus styles, semantic sections and ARIA labels
- Contact form opens the visitor's email app (`mailto:`), so no backend is needed

## Deploy

Upload `portfolio.html` (rename it to `index.html`) to any static host:

- **GitHub Pages:** push to a repo, then Settings, Pages, choose the branch
- **Netlify / Vercel:** drag and drop the folder

To host the resume, put `Asha_S_Resume.pdf` next to `index.html` and set the resume links to `Asha_S_Resume.pdf`.

## Contact

- GitHub: https://github.com/ashasaravanabalan-coder
- LinkedIn: https://www.linkedin.com/in/ashasaravanabalan/
- Email: sahsa628617@gmail.com
