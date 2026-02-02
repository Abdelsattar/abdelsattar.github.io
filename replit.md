# Mohamed Mostafa - Portfolio Website

## Overview
A modern, professional portfolio website for Mohamed Mostafa, a Senior Android Engineer based in Berlin with 9+ years of experience. The website showcases professional experience, skills, and projects in a creative and visually appealing way.

## Project Structure
- `index.html` - Main portfolio page with sections for About, Experience, Skills, Projects, and Contact
- `assets/` - Contains CSS, JavaScript, fonts, and SASS files
  - `css/modern.css` - Main modern stylesheet with responsive design
  - `js/modern.js` - Interactive JavaScript for animations and navigation
- `images/` - Image assets
  - `profile-new.jpg` - Current profile photo (Google I/O Connect Berlin)
  - `fulls/` - Full-size project images
  - `thumbs/` - Thumbnail images

## Sections
1. **Hero** - Introduction with name, title, stats, and call-to-action buttons
2. **About** - Professional summary with highlight cards
3. **Experience** - Timeline of professional journey (6 companies)
4. **Skills** - Technical arsenal organized by category
5. **Projects** - Featured projects including Just Eat Takeaway and JUCR
6. **Contact** - Contact information and social links

## Development
This is a static website served via Python's HTTP server on port 5000.

To run locally:
```
python -m http.server 5000 --bind 0.0.0.0
```

## Technologies
- HTML5, CSS3, JavaScript (Vanilla)
- Inter font family for typography
- Font Awesome 6.4 for icons
- Responsive design with CSS Grid and Flexbox
- Smooth scroll and intersection observer animations

## Deployment
Configured as a static site deployment serving files from the root directory.
