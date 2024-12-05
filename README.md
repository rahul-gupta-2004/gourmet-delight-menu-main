# Title: Lighthouse-Optimized Gourmet Delights Menu

Welcome to the Gourmet Delights Menu project! This repository contains the code and resources used to build and optimize a dynamic menu page for Gourmet Delights Restaurant. The project leverages XML for menu item management and includes Lighthouse JS performance reports to ensure a high-quality user experience.

## Overview

The Gourmet Delights Menu showcases a range of gourmet dishes with dynamically loaded content. The site features a responsive design and is optimized for performance and accessibility.

## Project Structure

- **images/**: Contains all images used in the project in `.webp` format.
- **original_files/**: Contains the original `index.html` and `style.css` files before testing.
- **index.html**: Updated `index.html` file after testing.
- **style.css**: Updated `style.css` file after testing.
- **menu.xml**: XML file with menu items.
- **report1.pdf**: First performance report using Lighthouse JS.
- **report2.pdf**: Second performance report using Lighthouse JS.

## Key Features

- **Dynamic Menu Loading**: The menu items are loaded dynamically using jQuery to fetch data from `menu.xml`.
- **Responsive Design**: The site adapts to various screen sizes using Bootstrap.
- **Image Optimization**: Images are served in `.webp` format for better performance, with fallback to other formats.

## Changes Made

### `index.html`
1. **Meta Description**: Added a meta description for better SEO.
2. **Image Formats**: Updated image formats from `.png` to `.webp` for better performance and added fallback support.
3. **ARIA Labels**: Added ARIA labels to improve accessibility.

### `style.css`
1. **Font Family**: Changed font family to "Helvetica Neue", Arial, sans-serif for a modern look.
2. **Background Color**: Updated the background color of cards to white and text color to dark gray for better contrast.
3. **Color and Font Adjustments**: Improved text color and font settings for better readability.

## Testing and Optimization

The project was tested using Lighthouse JS, which evaluates the performance, accessibility, best practices, and SEO of the webpage. Here are the results:

- **Report 1**:
  - Performance: 41
  - Accessibility: 95
  - Best Practices: 100
  - SEO: 91

- **Report 2**:
  - Performance: 92
  - Accessibility: 95
  - Best Practices: 100
  - SEO: 91

The performance score improved significantly from the first to the second report, reflecting the optimizations made.
