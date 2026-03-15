# Love Running

Love Running is a responsive multi-page website for a fictional running club based in Dublin, Ireland.
The project showcases core front-end skills using semantic HTML and CSS, with a focus on layout, responsiveness, accessibility basics, and clean navigation across pages.

## Project Overview

This website was built as a practice project to demonstrate:

- Semantic page structure with HTML5
- Mobile-first responsive design with CSS media queries
- Consistent navigation and branding across multiple pages
- Form creation and validation using native HTML attributes
- Basic accessibility practices (alt text, labels, aria-labels)

The site includes three pages:

- `index.html`: Home page with hero section, club benefits, and meetup schedule
- `gallery.html`: Photo gallery of running-related images
- `signup.html`: Membership form with text inputs and radio button preferences

## Features

- Fixed header with responsive navigation
- Hero section with callout panel
- Benefits section with visual and text content
- Meetup schedule cards over a background image
- Responsive gallery layout using CSS columns
- Sign-up form with required field validation
- Social links in the footer
- Font Awesome icon integration

## Technologies Used

- HTML5
- CSS3
- Google Fonts (`Lato`, `Oswald`)
- Font Awesome

## Project Structure

```text
love-running/
	index.html
	gallery.html
	signup.html
	README.md
	CSS/
		Style.css
	Assets/
		images/
		Favicon/
```

## How To Run Locally

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Open `index.html` directly in a browser, or use the VS Code Live Server extension for local development.

## Testing

Manual checks completed during development:

- Navigation links work across all pages.
- Layout adapts at common breakpoints (`576px`, `768px`, `992px`, `1200px`).
- Form fields enforce required inputs and email format.
- Images include descriptive `alt` text.
- External social links open in a new tab.

### Notes

- Path casing is mixed in the current project (`Assets/` folder vs references like `assets/` in some HTML files). This may work on Windows but can break on case-sensitive hosts. Normalizing path casing is recommended before deployment.

## Deployment

This project can be deployed as a static site using services such as:

- GitHub Pages
- Netlify
- Vercel

Basic GitHub Pages flow:

1. Push the project to a GitHub repository.
2. Open repository `Settings`.
3. Go to `Pages`.
4. Set source to the main branch and root folder.
5. Save and wait for the published URL.

## Future Improvements

- Add a custom 404 page
- Improve color contrast and keyboard focus states further
- Add lightweight JavaScript for interactive enhancements
- Add automated validation/linting in CI

## Credits

- Project concept inspired by common front-end training exercises for responsive websites.
- Icons by [Font Awesome](https://fontawesome.com/)
- Fonts by [Google Fonts](https://fonts.google.com/)

