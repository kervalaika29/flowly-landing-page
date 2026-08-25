# Flowly — Landing Page

A single-page product landing page built with plain HTML and CSS (no
JavaScript, no build tools) as coursework for **Programming from
Zero**. The FAQ accordion uses the native `<details>`/`<summary>`
elements, so it's interactive without any JS.

## Structure

Everything lives in one `index.html` — header, hero, features,
pricing, FAQ, and footer — with the CSS inline in a `<style>` block
so the page is self-contained and easy to preview. Each section is
marked with a comment banner.

## Viewing it

Open `index.html` in a browser — no server or build step needed.

## Formatting

```bash
npm install
npm run format
```

## How this repo was built

`setup.sh` (one directory up from here once generated) creates this
repository on GitHub and adds each section on its own branch, merged
into `main` through a real Pull Request:

1. `feature/hero-section`
2. `feature/features-section`
3. `feature/pricing-section`
4. `feature/faq-section`
5. `feature/footer-section`
