# Netflix Clone

This project is a clone of the Netflix homepage designed to showcase a variety of features and design principles. The page includes sections for a call-to-action, feature highlights, FAQs, and a footer. It is styled with modern CSS techniques and designed to be responsive for different screen sizes.

## Features

- **Header**: Includes a logo and a "Sign in" button.
- **Main Container**: Features a main title, subtitle, call-to-action, and email input section for creating or restarting a membership.
- **Features Section**: Showcases various Netflix features with text and images.
- **FAQ Section**: An accordion-style FAQ section for common questions.
- **Footer**: Contains links to various Netflix-related resources and a language selection button.

[![Netlify Status](https://api.netlify.com/api/v1/badges/e6571d10-3b21-4176-b18b-be25fd9cdce3/deploy-status)](https://app.netlify.com/sites/nfx-cloneby-tabsheera/deploys)

## Technologies Used

- **HTML**: For the structure of the webpage.
- **CSS**: For styling the webpage, including responsiveness and animations.
- **@font-face**: To include custom fonts for a consistent look.

## Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```bash
    cd <project-directory>
    ```
3. Open `index.html` in your web browser to view the project.

## File Structure

- `index.html`: The main HTML file for the project.
- `style.css`: The CSS file containing all styles and media queries.
- `image/`: Directory containing images used in the project.

## Image of Netflix Logo

![Netflix Logo](image/netflix_macos_bigsur_icon_189917.png)

## Custom Font

The project uses a custom font for the Netflix logo and other text. Ensure the font file is correctly referenced in your `style.css`:
```css
@font-face {
    font-family: 'Netflix-Sans-Regular';
    src: url('path/to/netflix-sans-regular.woff2') format('woff2');
    font-weight: normal;
    font-style: normal;
}

