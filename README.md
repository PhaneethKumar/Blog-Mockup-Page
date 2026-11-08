# Blog Mockup: Semantic HTML Practice

A static blog homepage built with semantic HTML only (no CSS or JavaScript). It is the HTML practice assignment from Microsoft's [Web Development for Beginners](https://github.com/microsoft/Web-Dev-For-Beginners) curriculum.

**Live demo:** <add your GitHub Pages / Netlify / Vercel link here>

![Screenshot of the blog homepage](screenshots/homepage.png)

## About the project

The goal was to plan a blog homepage first, then turn that plan into clean, accessible markup. The page includes:

- A header with the site title and main navigation
- A main content area with several blog post previews
- A sidebar with an about section, recent posts, and categories
- A footer with contact information and links

The page looks plain on purpose. This assignment focuses on structure and meaning, and styling comes later with CSS.

## Project structure

```
.
├── index.html          # Blog homepage
├── mockup/             # Labeled visual mockup (sketch or wireframe)
├── screenshots/        # Screenshots used in this README
└── README.md
```

## Semantic elements used

| Purpose | Elements |
|---------|----------|
| Page layout | `<header>`, `<nav>`, `<main>`, `<section>`, `<aside>`, `<footer>` |
| Blog content | `<article>`, `<h1>`, `<h2>`, `<h3>`, `<p>`, `<time>`, `<blockquote>` |
| Lists and links | `<ul>`, `<li>`, `<a>` |
| Media and emphasis | `<img>`, `<strong>`, `<em>` |

## Accessibility and best practices

- `lang` attribute set on the `<html>` element
- A single `<h1>`, with headings nested in order (`h1` → `h2` → `h3`)
- Descriptive `alt` text on every image
- Link text that makes sense out of context (no "click here")
- `<time>` elements with machine-readable `datetime` values
- Comments marking each major section of the code
- Checked with the [W3C HTML Validator](https://validator.w3.org/)

## Design planning

Before writing any code, I sketched a mockup of the homepage and labeled each section with the HTML element I planned to use for it (for example, "Header → `<header>`", "Blog post → `<article>`"). You can find it in the [`mockup/`](mockup/) folder.

## Run it locally

No build step or dependencies are needed.

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

Then open `index.html` in any browser.

## Reflection

<Paste your 3-5 sentence reflection here. Cover: the elements you felt most confident using, the challenges you ran into, how semantic HTML helped organize your content, and what you'd do differently next time.>

## What's next

- [ ] Style the page with CSS (layout, typography, responsive design)
- [ ] Add a skip-to-content link and test with a screen reader
- [ ] Turn the static post previews into full post pages

## Credits

Assignment from [Web Development for Beginners](https://github.com/microsoft/Web-Dev-For-Beginners) by Microsoft. All code and content in this repository are my own work.