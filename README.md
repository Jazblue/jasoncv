![Visitors](https://visitor-badge.laobi.icu/badge?page_id=Jazblue.jasoncv)

# JasonCV - Personal Portfolio & Resume

A modern, interactive CV/portfolio website showcasing Jason Harvey's professional background, skills, and achievements.

## Overview

JasonCV is a dynamic web application designed to present a comprehensive digital resume. Built with modern web technologies, it offers an engaging way to display professional qualifications and career progression.

## Key Features

- **Interactive Portfolio**: Browse through projects and professional experience
- **Responsive Design**: Works seamlessly across all devices and screen sizes
- **Modern Tech Stack**: Built with React, TypeScript, and modern CSS frameworks
- **Smooth Animations**: Engaging transitions and micro-interactions
- **Accessibility Compliant**: WCAG 2.1 AA standard compliance
- **SEO Optimized**: Structured data and meta tags for better search visibility

## Technical Specifications

### Frontend
- **Framework**: React 18+ with TypeHub
- **Language**: TypeScript
- **Styling**: Tailwind CSS with custom animations
- **Routing**: React Router
- **State Management**: Zustand
- **Build Tool**: Vite

### Backend
- **API**: JSON server (included for development)
- **Deployment**: Deployable to Vercel, Netlify, or GitHub Pages

### Performance
- **Bundle Size**: Optimized for fast loading
- **Lighthouse Score**: 90+ across all categories
- **Core Web Vitals**: Optimized for user experience

## Project Structure

```
jasoncv/
├── src/
│   ├── components/        # Reusable UI components
│   ├── pages/            # Individual page routes
│   ├── assets/           # Images, icons, and assets
│   ├── services/         # API and utility services
│   └── styles/           # Global styles and variables
├── public/                # Static assets
├── tests/                 # Test suite
└── docs/                  # Documentation
```

## Getting Started

### Prerequisites

- Node.js 16+
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/Jazblue/jasoncv.git
cd jasoncv

# Install dependencies
npm install

# Run development server
npm run dev
```

### Building for Production

```bash
# Build for production
npm run build

# Preview build locally
npm run preview
```

## Usage

### Development
Run the development server:

```bash
npm run dev
```

Open `http://localhost:3000` to view the application in your browser.

### Preview Build
Preview your production build:

```bash
npm run preview
```

### Testing

Run the test suite:

```bash
npm test
```

### Deployment

This project is configured for deployment to:

- **Vercel**: Run `vercel deploy`
- **Netlify**: Run `netlify deploy`
- **GitHub Pages**: Configure `gh-pages` branch

## Features

### Professional Summary
- Dynamic professional headline that updates based on screen size
- Interactive skill progression indicators
- Timeline visualization of career progression

### Project Gallery
- Grid and list views for project presentation
- Filter and search functionality
- Project detail modals with comprehensive information
- Live demo links and source code access

### Experience Timeline
- Interactive timeline visualization
- Hover details with expandable information
- Color-coded categories (Work, Education, Skills)
- Animated transitions and micro-interactions

### Skills Section
- Progress bars with percentage indicators
- Category-based organization
- Interactive skill tooltips
- Real-time validation and filtering

### Contact Section
- Multiple contact method options
- Form submission with validation
- Social media integration
- Email address protection against spam

## Technologies Used

### Frontend
- React 18+
- TypeScript
- Tailwind CSS
- Zustand
- React Router
- Vite
- Lucide React (icons)

### Backend
- JSON server
- Node.js scripts
- Environment variables

### Tools
- ESLint
- Prettier
- Husky
- lint-staged
- Jest (testing)
- Playwright (E2E testing)

## Development Workflow

1. **Setup**: Clone and run `npm install`
2. **Code**: Follow ESLint and Prettier standards
3. **Test**: Run tests frequently
4. **Build**: Use `npm run build` for production
5. **Deploy**: Use your preferred platform

## Project Status

This project is actively maintained and under active development. New features and improvements are added regularly based on user feedback and emerging web technologies.

## Contributing

Contributions are welcome! Please:

1. Fork the repository
2. Create a feature branch
3. Follow the code style guidelines
4. Add tests for new functionality
5. Submit a pull request

## License

MIT License - See `LICENSE` file for details.

## Acknowledgments

Special thanks to:
- The open-source community for invaluable libraries
- Contributors who have enhanced this project
- Users who provide feedback and suggestions
- All the tools and services that make modern web development possible

---

*Made with ❤️ by Jason Harvey*

*Repository: https://github.com/Jazblue/jasoncv*
*Live Demo: https://jasoncv.vercel.app*
