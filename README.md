# ExploreWorld — Travel & Tourism Website

A modern, responsive Travel & Tourism Website developed using HTML5 and CSS3 as part of a Week 1 frontend development assignment.

## Live Deployment & Repository

- **Live URL**: [https://exploreworld-travel-website-nine.vercel.app/](https://exploreworld-travel-website-nine.vercel.app/)
- **GitHub Repository**: [https://github.com/gamepatt78/exploreworld-travel-website](https://github.com/gamepatt78/exploreworld-travel-website)

## Project Overview

ExploreWorld is a travel website designed to showcase popular international travel destinations, holiday packages, travel highlights, and an enquiry form. The website provides a clean, user-friendly, and elegant interface that adapts smoothly across desktop, tablet, and mobile screens.

## Features

- Responsive navigation bar with brand identity and anchor links
- Attractive hero section with background imagery and dual call-to-action buttons
- Six popular travel destinations: Goa, Bali, Paris, Dubai, Maldives, and Swiss Alps
- Three holiday packages featuring Indian Rupee (₹) pricing, durations, and itineraries
- About Us section highlighting brand mission and personalized itinerary planning
- Why Choose Us section featuring four service highlights
- Minimalist Contact / Enquiry form with HTML5 validation and 10-digit Indian phone number constraint
- Modern multi-column footer with quick navigation links, services, and copyright info
- Responsive layouts built with CSS Grid and Flexbox
- Focus and hover states for accessible keyboard navigation
- Support for `prefers-reduced-motion` for enhanced accessibility

## Technologies Used

- HTML5 (Semantic elements, form validation, accessible attributes)
- CSS3 (Custom properties/variables, CSS Grid, Flexbox, media queries)
- Google Fonts (Plus Jakarta Sans & Playfair Display)
- Royalty-free photography from Unsplash

## Project Structure

```text
exploreworld-travel-website/
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── hero.jpg
│   ├── goa.jpg
│   ├── bali.jpg
│   ├── paris.jpg
│   ├── dubai.jpg
│   ├── maldives.jpg
│   ├── switzerland.jpg
│   └── about.jpg
├── exploreworld-travel/
│   ├── index.html
│   ├── css/
│   │   └── style.css
│   └── images/
└── README.md
```

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/gamepatt78/exploreworld-travel-website.git
   ```
2. Open the project folder in your preferred code editor (such as VS Code).
3. Open `index.html` in any web browser, or launch it with Live Server.
4. Explore the website and test responsive layouts.

## Responsive Design

The website uses mobile-first principles and CSS media queries to support a wide range of devices:

- **Desktop (1024px – 1920px)**: 3-column destination and package grids, full desktop navigation bar.
- **Tablet (768px – 1023px)**: 2-column cards, adjusted spacing and column alignments.
- **Mobile (320px – 767px)**: Single-column stacked cards, responsive navigation links, full-width touch-friendly form inputs and buttons.

## Contact Form

The enquiry form demonstrates HTML5 input fields and browser validation. It includes standard 10-digit Indian mobile number validation (`pattern="[6-9][0-9]{9}"` with `maxlength="10"`). It is a frontend-only demonstration and does not send or store enquiries.

## Future Enhancements

- Functional enquiry submission via serverless API or email service
- Dynamic destination search and filtering
- Interactive currency converter and travel package customization
- Real-time booking and payment gateway integration
- Multi-language translation support

## Author

Athwin Videsh M

## License

This project is intended for educational and portfolio purposes. Third-party images remain subject to their respective Unsplash licenses.
