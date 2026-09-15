# Department of Cybersecurity Website — Exercise 1 (CYB325)

## Overview
A 3-page semantic HTML5 website for the Department of Cybersecurity at
Taibah University, built for the CYB325 HTML Fundamentals lab.

## File Structure
- `index.html` — Homepage: welcome section, campus image, and news/announcements
- `about.html` — About page: department history and mission statement
- `programs.html` — Programs page: course listing and degree requirements
- `images/campus.jpg.jpg` — Photo of the Taibah University campus

## Semantic Structure Used
- `<header>` and `<nav>` for site identity and navigation (present on every page)
- `<main>` as the primary content area
- `<section>` to group related content (Welcome, News, History, Mission,
  Course Listing, Degree Requirements)
- `<article>` for individual news items
- `<figure>` / `<figcaption>` for the campus image with a caption
- `<footer>` with copyright and contact email on every page
- `<time datetime="...">` for machine-readable dates

## Features
- Ordered and unordered lists for course listings and degree requirements
- Descriptive `alt` text on the campus image for accessibility
- Contact email link (`mailto:`)
- Consistent navigation menu across all three pages

## How to Run
1. Open the `cyb-dept-site` folder in VS Code.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click `index.html` → **Open with Live Server**.
4. Navigate between Home, About, and Programs using the top menu.

## Notes
- `images/campus.jpg.jpg` should be renamed to `campus.jpg` for a cleaner
  file name before final submission (remember to update the `src` in
  `index.html` if renamed).
  