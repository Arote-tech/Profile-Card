# Profile Card

This project is a simple static profile card built with HTML and CSS. It displays a user avatar, name, role, live time, bio, social links, and two side-by-side profile sections for hobbies and dislikes.

## Overview

- **Static layout:** `index.html` contains the card structure and content.
- **Styling:** `style.css` handles the visual design, including the top colored header and card layout.
- **Live time:** the time element updates automatically with a small JavaScript snippet.
- **Responsive card:** designed to keep content aligned and arranged in a clean card format.

## Project Structure

- `index.html` — main HTML document for the profile card.
- `style.css` — CSS styles for layout, colors, spacing, and responsive behavior.
- `README.md` — project documentation.
- `package.json` — basic npm metadata (not required for the static profile card).

## Features

- Colored top section that fills the top of the profile card.
- Avatar and profile text stacked vertically in the header.
- User role and time displayed inside the colored header section.
- Social icon links with hover styling.
- Two separate sections for **Hobbies** and **Dislikes**, laid out side by side.
- Accessible HTML structure with semantic elements and ARIA labels.

## Installation

This project is mainly static and does not require a build step.

1. Clone or download the repository.
2. Open `index.html` directly in a web browser.

If you want to use npm tools for package management or future development:

```bash
cd "C:\Projects\Profile Card"
npm install
```

## Usage

To preview the profile card:

1. Open `index.html` in your browser.
2. The profile card appears centered on the page.
3. The top red header fills the card's header area, and the content should remain aligned vertically.

## Customization

- Change the avatar image by editing the `src` attribute in `index.html`.
- Update the user name, role, bio, hobbies, and dislikes directly in `index.html`.
- Adjust colors, spacing, and layout in `style.css`.

## Accessibility

- The page uses proper semantic elements like `<article>`, `<figure>`, `<section>`, `<h2>`, and `<ul>`.
- The avatar includes an `alt` attribute.
- Social links are keyboard accessible.
- The language of the document is set in the `<html lang="eng">` attribute.

## Notes

This profile card is a lightweight example of a personal UI component. It is best suited for learning HTML/CSS layout and simple interactive design.
