# SIDBI DOM XSS PoCs

## ✅ PoC 1 – DOM XSS via input → innerHTML
- File: `dom-xss-level2.html`
- Vector: Unescaped user input into `innerHTML`

## ✅ PoC 2 – DOM XSS via anchor.href (path injection)
- File: `dom-xss-anchor.html`
- Vector: `location.pathname.split('/').pop()` → assigned to `a.href`
