# Blog Mockup: Semantic HTML Practice

A static blog homepage built with semantic HTML & CSS. It is the HTML practice assignment from Microsoft's [Web Development for Beginners](https://github.com/microsoft/Web-Dev-For-Beginners) curriculum.

**Live demo:** <https://phaneethkumar.github.io/Blog-Mockup-Page/>

## About the project

The goal was to plan a blog homepage first, then turn that plan into clean, accessible markup. The page includes:

- A header with the site title and main navigation
- A main content area with several blog post previews
- A sidebar with an about section, recent posts, and categories
- A footer with contact information and links

The page looks plain on purpose.

## Project structure

```
.
├── .github/workflows/   # GitHub Actions workflow(s)
├── README.md
├── index.html           # Blog homepage
└── style.css            # Styling for the page
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

Before writing any code, I have chosen a blog page mockup from Figma community and labeled each section with the HTML element I planned to use for it using Figma Dev mode. You can find the mockup [here](https://www.figma.com/design/bupLR61kE85RWWtdifOXQ4/Blog-Home-Page?node-id=0-1&p=f).

## Run it locally

No build step or dependencies are needed.

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

Then open `index.html` in any browser.

## Credits

Assignment from [Web Development for Beginners](https://github.com/microsoft/Web-Dev-For-Beginners) by Microsoft. All code and content in this repository are my own work.