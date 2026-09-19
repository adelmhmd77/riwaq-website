# 📚 Riwaq Library (مَكْتَبَةُ رِوَاق)

An Arabic-language online bookstore front-end that presents novels, featured authors, literary news and store highlights in a single static page.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font%20Awesome-6.7.2-528DD7?logo=fontawesome&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-222?logo=github&logoColor=white)

[**Live Demo**](https://adelmhmd77.github.io/riwaq-website/)

<img width="918" height="476" alt="image" src="https://github.com/user-attachments/assets/443dac20-6be4-4dab-87fa-51a89b8539c4" />

---

## Overview

**Riwaq Library** (*مَكْتَبَةُ رِوَاق*, tagline: "هُنَا تَبْدَأُ الرِّوَايَةُ") is a bookstore landing page written in plain HTML and CSS. It features Arabic novels with cover images, prices and short descriptions, highlights of featured authors, a literary news section and a store-services strip.

It is a front-end/UI project only. See [Notes](#notes) for what is and isn't functional.

## Features

- **Header and navigation:** social icon links, top links, a main menu with a "More" dropdown (pages and blog), and search, account and cart icons.
- **Hero section:** a slider track of book covers with an introduction to the library.
- **Featured authors:** cards for Osama Al-Muslim, Amr Abdel Hamid and Ahmed Al-Hamdan.
- **Latest novels and books:** cards with cover, title, price with a struck-through original price, star rating, description, and heart / cart / zoom icons.
- **Latest novels in the library:** a second row of four titled cards with prices.
- **Testimonial:** a quote from the site's developer.
- **Literary news:** three news cards, two of which link to external articles.
- **Store highlights:** fast shipping, curated novels, multiple payment methods and simple UI.
- **Footer:** newsletter input, quick links, categories, services and support link groups.

## Technologies

| Technology | Usage |
| --- | --- |
| HTML5 | Page structure (`index.html`) |
| CSS3 | Styling via `css/style.css`, `css/reset.css` and `css/shortcuts.css` |
| [Font Awesome 6.7.2](https://fontawesome.com/) | Icons, loaded from cdnjs |

No JavaScript file or `<script>` tag is present in the project.

## Getting Started

### Prerequisites

- A modern web browser.
- Internet access, so Font Awesome can load from the CDN.

### Installation

```bash
git clone https://github.com/adelmhmd77/riwaq-website.git
cd riwaq-website
```

No dependencies or build step are required.

### Usage

Open `index.html` directly in your browser, or serve the folder with any static server.

## Project Structure

```text
riwaq-website/
├── css/
│   ├── style.css
│   ├── reset.css
│   └── shortcuts.css
├── fonts/
├── images/
├── index.html
└── README.md
```

- `css/`: stylesheets referenced by `index.html`.
- `fonts/`: font assets folder.
- `images/`: book covers, news images and the developer photo.

## Live Demo

[https://adelmhmd77.github.io/riwaq-website/](https://adelmhmd77.github.io/riwaq-website/)

## Repository

[GitHub Repository](https://github.com/adelmhmd77/riwaq-website)

## License

Not specified

## Notes

- **Static demo:** the project contains no backend, and no JavaScript is present in the HTML.
- **Non-functional elements:** most navigation and footer links point to `#`, and cart, favorites, search, account and newsletter controls are visual only.
- **Sample content:** the book catalog, prices and ratings are hard-coded in the HTML and appear to be demo data.
- **External resources:** icons load from the cdnjs CDN. Two news cards link to external news sites.
- **Deployment:** hosted on GitHub Pages.

## Author

**Adel Mohamed (عادل محمد)**: [@adelmhmd77](https://github.com/adelmhmd77)
