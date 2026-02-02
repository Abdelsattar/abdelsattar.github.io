# Sattar Portfolio Website

## Overview
A personal portfolio website for Mohammed Abd EL-Sattar, an Android developer and freelance software engineer from Cairo, Egypt. This is a static HTML/CSS/JS website built using the Strata template from HTML5 UP.

## Project Structure
- `index.html` - Main portfolio page
- `assets/` - Contains CSS, JavaScript, fonts, and SASS files
  - `css/` - Stylesheets
  - `js/` - JavaScript files (jQuery, poptrox, skel, etc.)
  - `fonts/` - Font files
  - `sass/` - SASS source files
- `images/` - Image assets
  - `fulls/` - Full-size project images
  - `thumbs/` - Thumbnail images
  - `profile.png` - Profile photo
  - `bg.jpg` - Background image

## Development
This is a static website served via Python's HTTP server on port 5000.

To run locally:
```
python -m http.server 5000 --bind 0.0.0.0
```

## Deployment
Configured as a static site deployment serving files from the root directory.
