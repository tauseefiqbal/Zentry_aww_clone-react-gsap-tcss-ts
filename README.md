# Award-Winning Website

A modern, interactive, and award-winning website built with React, featuring stunning animations and a beautiful user interface.

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Deployment](#deployment)
- [How to Use App for Regular User](#how-to-use-app-for-regular-user)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Setup Steps](#setup-steps)
- [Development](#development)
  - [Available Scripts](#available-scripts)
  - [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features

✅ **Responsive Design** - Fully responsive layout that works seamlessly across all devices and screen sizes

✅ **Smooth Animations** - Advanced GSAP-powered animations for enhanced user experience

✅ **Interactive Components** - Engaging 3D tilt effects and hover interactions on UI elements

✅ **Modern UI/UX** - Clean and contemporary design following latest web design trends

✅ **Hero Section** - Eye-catching hero section with dynamic content and visuals

✅ **About Section** - Comprehensive information about the project or brand

✅ **Features Showcase** - Interactive Bento grid layout displaying key features

✅ **Story Section** - Engaging narrative section with multimedia content

✅ **Contact Form** - Easy-to-use contact section for user inquiries

✅ **Fast Performance** - Optimized build with Vite for lightning-fast load times

✅ **SEO Friendly** - Structured for optimal search engine visibility

✅ **Cross-Browser Compatible** - Works flawlessly on all modern browsers

---

## Tech Stack

**Frontend Framework:**
- [React](https://reactjs.org/) (v18.3.1) - JavaScript library for building user interfaces
- [Vite](https://vitejs.dev/) (v8.2.1) - Next-generation frontend build tool

**Styling:**
- [Tailwind CSS](https://tailwindcss.com/) (v3.4.14) - Utility-first CSS framework
- [PostCSS](https://postcss.org/) (v8.4.49) - Tool for transforming CSS
- [Autoprefixer](https://github.com/postcss/autoprefixer) (v10.4.20) - CSS vendor prefixing

**Animation Libraries:**
- [GSAP](https://greensock.com/gsap/) (v3.12.5) - Professional-grade animation library
- [@gsap/react](https://www.npmjs.com/package/@gsap/react) (v2.1.1) - GSAP React integration

**Utilities:**
- [React Icons](https://react-icons.github.io/react-icons/) (v5.3.0) - Icon library
- [clsx](https://github.com/lukeed/clsx) (v2.1.1) - Utility for constructing className strings
- [react-use](https://github.com/streamich/react-use) (v17.5.1) - Collection of React Hooks

**Development Tools:**
- [ESLint](https://eslint.org/) (v9.14.0) - JavaScript linting utility
- [Prettier](https://prettier.io/) (v3.3.3) - Code formatter
- TypeScript types for React and React DOM

---

## Deployment

### Live Application

🌐 **Live URL:** [APP URL]

The application is deployed and accessible at the URL above. Visit the link to experience the full interactive website.

### Deployment Information

- **Build Command:** `npm run build`
- **Output Directory:** `dist`
- **Node Version:** 18.x or higher recommended

---

## How to Use App for Regular User

### Navigating the Website

1. **Homepage (Hero Section)**
   - Start at the landing page with an engaging hero section
   - Scroll down or use the navigation menu to explore different sections

2. **Exploring Features**
   - Hover over feature cards to see interactive 3D tilt effects
   - Click on elements to learn more about specific features

3. **Reading the Story**
   - Navigate to the Story section to learn about the project narrative
   - Enjoy smooth scroll animations as you move through the content

4. **Contacting**
   - Scroll to the Contact section at the bottom
   - Fill out the contact form to get in touch
   - All interactive elements respond to hover and click events

5. **Navigation**
   - Use the top navigation bar to jump to any section instantly
   - The navbar stays accessible throughout your browsing experience
   - Mobile users can access the menu through the hamburger icon

### Tips for Best Experience

- **Use a modern browser** (Chrome, Firefox, Safari, or Edge) for optimal performance
- **Enable JavaScript** for full functionality and animations
- **Desktop users** can enjoy enhanced hover effects and interactions
- **Mobile users** will experience touch-optimized interactions

---

## Installation

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v18.x or higher) - [Download here](https://nodejs.org/)
- **npm** (v9.x or higher) or **yarn** (v1.22.x or higher)
- A code editor like [VS Code](https://code.visualstudio.com/)

### Setup Steps

1. **Clone the repository**

```bash
git clone <repository-url>
cd award-winning-website-main
```

2. **Install dependencies**

Using npm:
```bash
npm install
```

Or using yarn:
```bash
yarn install
```

3. **Start the development server**

Using npm:
```bash
npm run dev
```

Or using yarn:
```bash
yarn dev
```

4. **Open your browser**

Navigate to `http://localhost:5173` (or the port shown in your terminal)

---

## Development

### Available Scripts

- **`npm run dev`** - Start the development server with hot module replacement
- **`npm run build`** - Build the application for production
- **`npm run preview`** - Preview the production build locally
- **`npm run lint`** - Run ESLint to check code quality

### Project Structure

```
award-winning-website-main/
├── public/                 # Static assets
│   ├── audio/             # Audio files
│   ├── fonts/             # Custom fonts
│   ├── img/               # Images
│   └── videos/            # Video files
├── src/
│   ├── assets/            # Source assets
│   ├── components/        # React components
│   │   ├── About.jsx      # About section
│   │   ├── AnimatedTitle.jsx
│   │   ├── Button.jsx     # Reusable button component
│   │   ├── Contact.jsx    # Contact form section
│   │   ├── Features.jsx   # Features showcase
│   │   ├── Footer.jsx     # Footer component
│   │   ├── Hero.jsx       # Hero section
│   │   ├── Navbar.jsx     # Navigation bar
│   │   ├── Story.jsx      # Story section
│   │   └── VideoPreview.jsx
│   ├── App.jsx            # Main App component
│   ├── index.css          # Global styles
│   └── main.jsx           # Entry point
├── eslint.config.js       # ESLint configuration
├── index.html             # HTML template
├── package.json           # Project dependencies
├── postcss.config.js      # PostCSS configuration
├── tailwind.config.js     # Tailwind CSS configuration
├── vite.config.js         # Vite configuration
└── README.md              # Project documentation
```

### Building for Production

To create an optimized production build:

```bash
npm run build
```

The build output will be in the `dist` directory, ready to be deployed to any static hosting service.

---

## Contributing

We welcome contributions! If you'd like to contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please ensure your code follows the existing style and passes all linting checks.

---

## License

This project is private and proprietary. All rights reserved.

---

## Contact

For questions, feedback, or support, please reach out through:

- **Website:** Visit our Contact section
- **Issues:** Open an issue on the repository
- **Email:** [Your contact email]

---

**Made with ❤️ using React and Vite**
