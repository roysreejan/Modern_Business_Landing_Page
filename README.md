# Quantro - Modern Business Landing Page

Quantro is a modern, responsive business landing page built with React, Tailwind CSS, and Framer Motion. It features a clean design, smooth animations, and reusable components to help businesses showcase their services and products effectively.

## Features

- **Responsive Design**: Fully responsive layout that works seamlessly on all devices.
- **Smooth Animations**: Powered by Framer Motion for engaging animations.
- **Reusable Components**: Modular and reusable React components for easy customization.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
- **Swiper Integration**: Interactive carousels for testimonials and other sections.
- **Customizable Pricing**: Dynamic pricing section with adjustable product count.

## Tech Stack and Dependencies

This project is built using the following technologies and libraries:

- **React**: A JavaScript library for building user interfaces.
- **React-DOM**: Provides DOM-specific methods for React.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **Framer Motion**: A library for creating smooth animations in React.
- **Swiper**: A modern touch slider for creating carousels.
- **Vite**: A fast build tool for modern web development.
- **ESLint**: A tool for identifying and fixing JavaScript code issues.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/roysreejan/Quantro
   ```
2. Navigate to the project directory:
   ```bash
   cd quantro
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
    ```bash
    npm run dev
    ```

5. Open your browser and navigate to   
   ```
   http://localhost:5173
   ```

## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the project for production.
- `npm run preview`: Preview the production build.
- `npm run lint`: Run ESLint to check for code issues.

## Folder Structure

```
Quantro/
├── public/               # Static assets
│   ├── fav-icon.png       # Favicon for the website
│   ├── vite.svg           # Vite logo
├── src/                  # Source code
│   ├── assets/           # Images and data files
│   │   ├── amazon.png
│   │   ├── data.js
│   │   ├── github-cover.png
│   │   ├── hero-image.png
│   │   ├── meundies.png
│   │   ├── monitor-card.webp
│   │   ├── react.svg
│   │   ├── sitepoint.png
│   │   ├── slack.png
│   │   ├── stats.webp
│   │   ├── woocommerce.png
│   ├── components/       # React components
│   │   ├── CompanyLogo.jsx
│   │   ├── FeaturesSection.jsx
│   │   ├── Footer.jsx
│   │   ├── Hero.jsx
│   │   ├── MonitorSection.jsx
│   │   ├── Navbar.jsx
│   │   ├── NewsletterSection.jsx
│   │   ├── PricingSection.jsx
│   │   ├── PurposeSection.jsx
│   │   ├── ScheduleSection.jsx
│   │   ├── ServicesSection.jsx
│   │   ├── TestimonialSection.jsx
│   ├── utils/            # Utility functions
│   │   ├── motion.js
│   ├── App.jsx           # Main application component
│   ├── App.css           # Global styles
│   ├── index.css         # Tailwind CSS configuration
│   ├── main.jsx          # Entry point for the React app
├── .vscode/              # VS Code settings
├── .gitignore            # Git ignore file
├── [package.json](http://_vscodecontentref_/0)          # Project metadata and dependencies
├── [vite.config.js](http://_vscodecontentref_/1)        # Vite configuration
├── [eslint.config.js](http://_vscodecontentref_/2)      # ESLint configuration
├── [README.md](http://_vscodecontentref_/3)             # Project documentation
├── vercel.json           # Vercel deployment configuration
└── index.html            # HTML template
```

## Deployment

This project is configured for deployment on [Vercel](https://vercel.com). The `vercel.json` file ensures that all routes are rewritten to `index.html` for a single-page application.
The live project is available at: `https://quantro.vercel.app/`

To deploy:

1. Install the Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Deploy the project:
   ```bash
   vercel
   ```

## Acknowledgments

- Built with ❤️ using React and TailwindCSS.
- Icons and images sourced from the project's assets folder.