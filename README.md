# gamastudio

Website for GAMA Studio, a residential interior design studio. Live at
[gamastudio.vercel.app](https://gamastudio.vercel.app).

Five static pages (home, about, services, projects, contact) in plain HTML, CSS and
JavaScript, with no framework and no build step.

- Responsive layout with a collapsible mobile menu.
- Rotating hero images, and a navigation bar that changes style once you scroll past the
  hero.
- Sections fade in on scroll using `IntersectionObserver`.

## Status

The contact form is front-end only. It validates input and shows a confirmation, but it
doesn't send anything yet. Connecting it to a form service or email backend is the
next step.

## Running locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```
