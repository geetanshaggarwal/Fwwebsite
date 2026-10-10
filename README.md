# FreeWorld website

The site for freeworld.co.in, served by GitHub Pages from `index.html` on `main`.

- `index.html` is the home page (roster, contact form), `songwriting/index.html` the songwriting services page and `label/index.html` the label & distribution page. They share the same inline styles, so a style change goes in all three.
- Buttons on the other pages link to `/?s=<subject>#contact`, which preselects the contact form subject.
- `CNAME` points Pages at freeworld.co.in.
- The contact form posts to FormSubmit, which emails studiofreeworld@gmail.com.
