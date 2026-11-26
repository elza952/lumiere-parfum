# Lumière Parfum

Lumière Parfum is a website for a luxury perfume brand and shop, built as a two-person university project. It is written in plain HTML, CSS and vanilla JavaScript, with no frameworks, and is structured so PHP/MySQL can be added in Phase 2.

## Project structure

```
lumiere-parfum/
├── index.html          Home: hero slider, featured perfumes, brand teaser
├── collection.html     Collection: perfume cards, filter by family, notes guide
├── about.html          About: brand story, perfumers, values, contact form
├── login.html          Login form
├── register.html       Registration form
├── css/
│   ├── style.css       Shared: variables, reset, header/nav, footer, buttons, forms
│   ├── home.css
│   ├── collection.css
│   ├── about.css
│   └── auth.css
├── js/
│   ├── main.js         Shared: mobile nav toggle, active link
│   ├── slider.js
│   ├── collection.js   Filter buttons
│   └── auth.js         Validation, show/hide password
└── images/
```

## Design system

| Token          | Value                                  |
| -------------- | -------------------------------------- |
| Ink black      | `#111111`                              |
| Ivory          | `#F8F4EC`                              |
| Champagne gold | `#C9A96E`                              |
| Deep plum      | `#4A2C3A`                              |
| Soft gray      | `#8A8580`                              |
| Heading font   | Cormorant Garamond                     |
| Body font      | Inter                                  |
| Spacing scale  | `--space-xs` to `--space-xl`           |
| Buttons        | `.btn` (gold fill) and `.btn-outline`  |

All colors, fonts and spacing are defined as CSS variables in `css/style.css` and reused on every page.

## Conventions

- Lowercase file names with no spaces.
- BEM-style class names such as `.card`, `.card__title`.
- No inline styles; layout is done with Flexbox.
- Code is formatted with Prettier (format on save is enabled in `.vscode/settings.json`).

## Pages

| Page            | File              | Content                                                       |
| --------------- | ----------------- | ------------------------------------------------------------- |
| Home            | `index.html`      | Hero slider, featured perfumes, brand teaser                  |
| Collection      | `collection.html` | Perfume cards filtered by scent family, fragrance notes guide |
| About           | `about.html`      | Brand story, perfumers, values, contact form                  |
| Login           | `login.html`      | Login form with show/hide password and validation             |
| Register        | `register.html`   | Registration form with varied input types and validation      |

Every page shares the same header, navigation menu and footer.

## Team

| Member   | GitHub                                                 | Responsibilities                                                     |
| -------- | ------------------------------------------------------ | -------------------------------------------------------------------- |
| Person A | [@elza952](https://github.com/elza952)                 | Project setup, shared header/footer, Home, slider, Collection        |
| Person B | [@medinarexheppi](https://github.com/medinarexheppi)   | Login, Register, form validation, show/hide password, About, buttons |
