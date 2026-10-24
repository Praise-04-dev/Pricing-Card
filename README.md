# Pricing Card

A responsive, three-tier pricing table built with HTML and Tailwind CSS. Stacks vertically on mobile and sits side by side on medium screens and up.

## Preview

| Plan       | Price   | Users | Storage | Support            |
|------------|---------|-------|---------|--------------------|
| Free       | $0/mo   | 10    | 2 GB    | Email              |
| Pro        | $15/mo  | 20    | 10 GB   | Priority email     |
| Enterprise | $29/mo  | 30    | 15 GB   | Phone and email    |

## Features

- Fully responsive layout (single column on mobile, three columns on `md` and up)
- Highlighted Enterprise card using a blue accent
- Clean card structure: title, price, feature list, call-to-action button
- No build step required

## Tech Stack

- HTML5
- [Tailwind CSS v4](https://tailwindcss.com/) via the browser CDN (`@tailwindcss/browser@4`)
- `style.css` for any custom styles (currently empty)

## Project Structure

```
.
├── index.html   # Page markup and Tailwind utility classes
├── style.css    # Custom styles (placeholder)
└── README.md
```

## Getting Started

1. Clone or download the project.
2. Open `index.html` in your browser.

An internet connection is needed, since Tailwind is loaded from a CDN.

## Customization

- **Plans and prices:** edit the card blocks in `index.html` (`<!-- CARD 1 -->`, `<!-- CARD 2 -->`, `<!-- CARD 3 -->`).
- **Features:** add or remove `<li>` items inside each card's `<ul>`.
- **Colors:** swap the `blue-700` and `gray-*` utility classes for your own palette.
- **Custom CSS:** add rules to `style.css`.

## Future Improvements

- Add a "Most popular" badge to the Pro plan
- Add a monthly/yearly billing toggle
- Replace the CDN with a Tailwind build for production
- Make the buttons link to real sign-up pages

## License

This project is open for personal and educational use.