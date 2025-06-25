# Portfolio Website - Replit Configuration

## Overview

This is a frontend developer portfolio website built with vanilla HTML, CSS, and JavaScript. The project showcases a modern, responsive design with smooth animations and interactive elements. It serves as a personal portfolio for "Mansi" featuring sections for home, about, skills, projects, and contact information.

## System Architecture

### Frontend Architecture
- **Technology Stack**: Pure HTML5, CSS3, and vanilla JavaScript
- **Design Approach**: Mobile-first responsive design with modern CSS Grid and Flexbox
- **Font System**: Google Fonts integration (Inter for body text, JetBrains Mono for code/accent elements)
- **Icon System**: Font Awesome 6.4.0 for consistent iconography
- **Animation Strategy**: CSS animations with JavaScript-triggered scroll-based effects

### Styling Architecture
- **CSS Organization**: Single stylesheet with CSS custom properties (variables) for consistent theming
- **Color System**: Dark theme with primary purple (#6366f1), secondary amber, and accent green colors
- **Typography Scale**: Systematic font sizing and spacing using CSS custom properties
- **Component-Based**: Modular CSS classes for reusable components

### JavaScript Architecture
- **Module Pattern**: Functional approach with initialization functions for different features
- **Event-Driven**: DOM content loaded initialization with event listeners for interactions
- **Feature Modules**: Separate functions for navigation, typing effects, scroll animations, skill bars, counters, contact form, and floating elements

## Key Components

### Navigation System
- Responsive navbar with mobile hamburger menu
- Scroll-based navbar styling changes
- Smooth scrolling navigation with active link highlighting
- Mobile-optimized menu with animated hamburger icon

### Interactive Elements
- Typing effect animation for dynamic text display
- Scroll-triggered animations for content reveal
- Animated skill progress bars
- Counter animations for statistics
- Contact form with validation and submission handling
- Floating elements for visual enhancement

### Responsive Design
- Mobile-first approach with breakpoint-based media queries
- Flexible grid systems for project showcases
- Adaptive typography and spacing
- Touch-friendly navigation for mobile devices

## Data Flow

### Static Content Delivery
1. HTML structure defines semantic page layout
2. CSS provides styling and responsive behavior
3. JavaScript enhances interactivity and animations
4. External fonts and icons loaded from CDNs

### User Interaction Flow
1. Page loads with initial animations
2. Navigation enables smooth scrolling between sections
3. Scroll events trigger reveal animations and navbar changes
4. Contact form handles user input validation and submission
5. Mobile menu provides touch-friendly navigation

## External Dependencies

### Content Delivery Networks
- **Google Fonts**: Inter and JetBrains Mono font families
- **Font Awesome**: Version 6.4.0 for iconography
- **CDN Strategy**: External resources for optimal caching and performance

### No Backend Dependencies
- Pure client-side application
- No database requirements
- No server-side processing needed

## Deployment Strategy

### Local Development Server
- **Python HTTP Server**: Simple static file serving on port 5000
- **Command**: `python3 -m http.server 5000`
- **Rationale**: Lightweight development server for testing and development

### Production Deployment Options
- **Static Hosting**: Suitable for Netlify, Vercel, GitHub Pages, or any static host
- **CDN Distribution**: Can be deployed to any CDN for global distribution
- **No Build Process**: Ready-to-deploy static files require no compilation

### Replit Configuration
- **Multi-language Support**: Node.js 20 and Python 3.11 modules configured
- **Workflow Automation**: Automated project startup with parallel task execution
- **Port Configuration**: Configured to serve on port 5000 with wait-for-port functionality

## Changelog

```
Changelog:
- June 25, 2025. Initial setup
- June 25, 2025. Updated statistics section and added Omnifood project
- June 25, 2025. Created comprehensive README.md for GitHub repository
```

## User Preferences

```
Preferred communication style: Simple, everyday language.
```

## Development Notes

### Code Organization
- **HTML**: Semantic structure with accessibility considerations
- **CSS**: Custom properties for maintainable theming and consistent spacing
- **JavaScript**: Functional programming approach with clear separation of concerns

### Performance Considerations
- **Minimal Dependencies**: Vanilla JavaScript reduces bundle size
- **Optimized Assets**: External CDN resources for fonts and icons
- **Lazy Loading**: Scroll-triggered animations prevent initial load blocking

### Accessibility Features
- **Semantic HTML**: Proper heading hierarchy and landmark elements
- **Keyboard Navigation**: Focus management for interactive elements
- **Screen Reader Support**: Appropriate ARIA labels and descriptions
- **Responsive Design**: Mobile-friendly touch targets and layouts