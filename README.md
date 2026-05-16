# Landscape

A modern, responsive digital marketing agency website built with HTML, CSS, and Tailwind CSS. This project showcases a professional digital marketing landing page with multiple sections including services, team, case studies, and contact forms.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Project Sections](#project-sections)
- [Dependencies](#dependencies)
- [License](#license)

## Overview

Landscape is a full-featured marketing agency website designed to showcase digital marketing services. The website features a modern design with smooth interactions, responsive layouts, and comprehensive information about services, team members, case studies, and client testimonials.

## Features

- **Responsive Design**: Mobile-first approach with responsive breakpoints for all devices
- **Service Showcase**: 6 different digital marketing services with detailed descriptions
- **Team Section**: Professional team member profiles with expertise details
- **Case Studies**: Real-world examples of successful campaigns
- **Testimonials**: Client feedback and success stories
- **Working Process**: Step-by-step guide to the agency's workflow
- **Contact Form**: Integrated contact and quote request system
- **Modern UI**: Gradient backgrounds, smooth animations, and professional typography
- **Interactive Elements**: Expandable details sections and interactive navigation

## Tech Stack

- **HTML5**: Semantic markup and structure
- **CSS3**: Custom styling and layouts
- **Tailwind CSS**: Utility-first CSS framework (v4.2.4)
- **Boxicons**: Icon library for visual elements

### Dependencies

```json
{
  "@tailwindcss/cli": "^4.2.4",
  "tailwindcss": "^4.2.4"
}
```

## Project Structure

```
landscape/
├── src/
│   ├── index.html          # Main landing page
│   ├── input.css           # Tailwind CSS input file
│   ├── output.css          # Compiled CSS output
│   └── .gitignore          # Git ignore rules
├── img/                    # Image assets directory
├── package.json            # Project dependencies
├── package-lock.json       # Dependency lock file
└── README.md              # This file
```

## Installation

1. **Clone the repository**
   ```bash
   git clone git@github.com:Oxbee27/landscape.git
   cd landscape
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Build CSS with Tailwind**
   ```bash
   npm run build
   ```

4. **Serve the website**
   - Open `src/index.html` in your web browser
   - Or use a local server like:
     ```bash
     npx http-server src
     ```

## Usage

### Development

To watch for changes and rebuild CSS automatically:

```bash
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

### Building for Production

```bash
npm run build
```

## Project Sections

### 1. **Header/Navigation**
- Fixed navigation bar with logo
- Navigation links (About, Services, Use Cases, Pricing, Blog)
- Mobile-responsive hamburger menu
- Call-to-action button

### 2. **Hero Section**
- Main headline: "Navigating the digital landscape for success"
- Subheading with value proposition
- Call-to-action button ("Book a consultation")
- Hero image

### 3. **Services Section**
Showcases 6 core services:
- Search Engine Optimization (SEO)
- Pay-per-click (PPC) Advertising
- Social Media Marketing
- Email Marketing
- Content Creation
- Analytics and Tracking

### 4. **Case Studies**
Real-world success stories including:
- Local restaurant PPC campaign results
- B2B software company SEO strategy
- National retail chain social media campaign

### 5. **Working Process**
6-step methodology:
1. Consultation
2. Research
3. Implementation
4. Optimization
5. Reporting
6. Improvement

### 6. **Team Section**
Professional team members with roles:
- John Smith - CEO and Founder
- Jane Doe - Director of Operations
- Michael Brown - Senior SEO Specialist
- Emily Johnson - PPC Manager
- Brian Williams - Social Media Specialist
- Sarah Kim - Content Creator

### 7. **Testimonials**
Client feedback carousel with navigation controls

### 8. **Contact Section**
Contact form with:
- Contact option selection (Say Hi / Get a Quote)
- Name, Email, and Message fields
- Submit button

### 9. **Footer**
- Company information
- Navigation links
- Social media links
- Newsletter subscription
- Copyright and credits

## Language Composition

- **HTML**: 55%
- **CSS**: 45%

## Color Scheme

- Primary: #99CD39 (Lime Green)
- Secondary: Black (#000000)
- Background: Light Gray (#f3f3f3)
- Accent: White (#FFFFFF)
- Dark: Gray-950, Gray-900

## Customization

### Colors
Update Tailwind colors in the HTML file by modifying class names:
- `bg-[#99CD39]` - Primary green
- `bg-black` - Black background
- `bg-[#f3f3f3]` - Light gray background

### Content
Edit the text content directly in `src/index.html` to customize:
- Service descriptions
- Team member details
- Case study information
- Testimonials

### Styling
Modify Tailwind classes in the HTML elements to customize:
- Spacing (mt-, px-, py-)
- Colors (bg-, text-)
- Layout (flex, grid)
- Responsive breakpoints (sm:, md:, lg:)

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Considerations

- Optimized CSS output (~24KB)
- Minimal external dependencies
- SVG and WebP image support
- Responsive image handling
- Modern CSS Grid and Flexbox layouts

## Features in Development

- [ ] Dark mode toggle
- [ ] Multiple language support
- [ ] Blog section
- [ ] Pricing calculator
- [ ] Advanced contact form validation
- [ ] Performance metrics tracking

## License

ISC - See LICENSE file for details

## Author

Oxbee27

## Credits

- Design and Development: Oxbee27
- Icons: Boxicons
- CSS Framework: Tailwind CSS
- Images: Various contributors

## Support

For issues, questions, or suggestions, please open an issue in the repository.

---

**Last Updated**: May 16, 2026

Made with ❤️ using HTML, CSS, and Tailwind CSS
