# BrightSpark-Electrical-Sevices-Website-WEDE5020

NAME:Sipho

SURNAME:Manyenkawu

ST10498640

MODULE NAME:Web Development

MODULE CODE:WEDE5020

# Project Overview 

Name: BrightSpark Electrical Services 

BrightSpark Electrical Services is a small local business that provides electrical installation, repairs, and maintenance for homes and small businesses. The company started in 2020 and has grown through word-of-mouth and local advertising. 

Mission: To provide safe, reliable, and affordable electrical services. 

Vision: To become a trusted electrician brand in the local community. 

Target Audience: 

Homeowners 

Small business owners 

Property managers 

 # Website Goals and Objectives 
The main goal of the website is to promote services and attract new customers.

Objectives: 

Increase online visibility 

Generate customer inquiries 

Provide service information

 KPIs: 
 
Number of website visits 

Contact form submissions 

Calls from the website 

# Website Features 

Homepage (business overview) 

About Us (company background) 

Services page (installations, repairs, maintenance) 

Contact page (form, phone number, location) 

# Timeline 

20 Feb – 26 Feb: 

Research and planning of the website project, including identifying the target audience and website content. 

27 Feb – 5 March: 

Create low-fidelity wireframes and plan the structure of each webpage (homepage, services, contact page). 

29 March– 20 April: 

Develop the website using HTML only, creating all main pages and adding content such as text, images, and links. 

 <img width="1024" height="768" alt="Pastel Pink and Peach Gradient Creative Agency Graph " src="https://github.com/user-attachments/assets/a5a80809-22b4-41f1-952b-d64598f2bfca" /> 

 ## Project Changelog 

### [v1.0.0] - Part 1 HTML Structure
#### Added
- **Multi-Page Architecture:** Created five core interconnected web pages (`index.html`, `about.html`, `services.html`, `enquiry.html`, `contact.html`) to form the site's structural baseline.
- **Semantic HTML5 Markup:** Utilized proper semantic structural containers, including `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>` elements across all documents to manage content flow.
- **Global Navigation System:** Implemented a unified top-header navigation link bar on every page to ensure seamless user routing across the entire website.
- **Responsive Media Embeds:** Integrated a functional, lazy-loading Google Maps interactive iframe on the contact layout page to display the physical branch location.
- **Interactive Multi-Input Form:** Constructed a multi-fieldset "Service Enquiry Form" complete with structured input types including text, email, telephone, custom range sliders, dropdown option selections, dates, and textareas. 
- **Media Asset Infrastructure:** Embedded relative graphic design source paths for core brand imagery, featuring dedicated product alt-text and structured width constraints.
  
# REFERANCE:

Mozilla Developer Network (2024) HTML basics. Available at: https://developer.mozilla.org

• W3Schools (2024) HTML Tutorial. Available at: https://www.w3schools.com

• Krug, S. (2014) Don't Make Me Think: A Common Sense Approach to Web Usability. 3rd edn. Berkeley: New Riders.

• WhatWG (2024) HTML Living Standard. Available at: https://html.spec.whatwg.org 

# BrightSpark Electrical Services Website - WED5020 POE Part 2

## Project Overview
This project is a fully functional corporate website developed for BrightSpark Electrical Services. It demonstrates semantic HTML5 architecture built in Part 1, enhanced with an external corporate-branded, fluid CSS design system completed in Part 2.

## Key Features
* **Semantic HTML5 Infrastructure:** Organized page components ensuring clean element flow.
* **Consistent Corporate Branding:** Custom color variables carefully matched to the BrightSpark corporate design brief.
* **Fluid Responsive Layout:** Multi-tier media query breakpoints ensuring seamless optimization across desktop, tablet, and mobile displays.
* **Interactive Controls:** Complete pseudo-class styling mapping (`:hover`, `:focus`, `:active`) across all form actions and navigation menus.

  ## Changelog

### [v2.0.0] - Part 2 Submission Updates
#### Added
- Implemented an external stylesheet (`style.css`) to isolate and manage site rules uniformly.
- Added comprehensive interactive pseudo-classes to enhance structural form tracking and user link clicks.
- Integrated standard media query breakpoints to naturally support mobile viewports.

#### Changed
- Refactored project directory hierarchy by grouping loose assignment markup into a designated `HTML` folder to fulfill structural curriculum requirements.
- Updated internal asset paths using explicit relative parameters (`../css/style.css`) to ensure consistent stylesheet linkage.

##  References
* MDN Web Docs. (2026). *Using CSS custom properties (variables)*. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties [Accessed: 10 May 2026].
* W3Schools. (2026). *CSS Responsive Web Design - Media Queries*. Available at: https://www.w3schools.com/css/css_rwd_mediaqueries.asp [Accessed: 10 May 2026].
* https://youtube.com/playlist?list=PLP9IO4UYNF0UCaUSF3XNZ1U9f01E5h5PM&si=pv2wzNz8jQM3cYt8
* https://youtu.be/8HkGwdUDOcc?si=OfRyXlV0To4F9kY8
* https://youtu.be/KCWFaZJx_Ig?si=XrZnlwGvTBFeoxBc


# BrightSpark Electrical Services Website - WED5020 POE Part 3

## project overview

BrightSpark Electrical Services is a responsive, multi-page web application designed for a local electrical service provider in Kuilsriver, Cape Town. Part 3 introduces the interactive client-side engine, shifting the site from a static brochure into a dynamic, user-centric platform. This phase focuses on vanilla JavaScript functionality, advanced form validation, local SEO, and fluid mobile responsiveness to fix previous display bugs on narrow smartphone screens (like iPhones).

Dynamic Search & Content Filter (services.html): A real-time JavaScript search input and category button filter (Installations, Repairs, Maintenance) that dynamically updates and displays matching service cards instantly without reloading the page.

Interactive Image Lightbox Modal (services.html): A pure JavaScript image viewer modal that displays a focused, semi-transparent screen overlay with high-resolution image previews and dynamic captions when clicked.

Defensive Form Validation (enquiry.html & contact.html): Added client-side logic to evaluate inputs (name strings, standard 10-digit South African mobile formatting, email regex patterns, range parameters, and date selections). Submissions bypass raw browser alert boxes to display stylized inline confirmation cards.

Fluid Mobile Responsiveness: Corrected broken viewport metadata tags (initial-scale=1.0) and applied unified scaling rules (max-width: 100%, box-sizing: border-box, flex-wrapping) to prevent content overflow and clipping on small displays.

Localized SEO & Asset Accessibility: Configured distinct <title> and <meta description> tags on all structural routes, removed redundant file extensions (.jpg.jpg), and assigned semantic alt attributes to visual assets.

## File Stucture

BrightSpark_Website/
│

├── HTML/ (index.html, about.html, services.html, enquiry.html, contact.html)

├── CSS/  (style.css - Central Design Tokens & Mobile Media Queries)

└── JS/   (script.js - Unified JavaScript System Engine)

## Changelog — BrightSpark Electrical Services Website

## [Version 3.3] 

### Fixed
- Fixed missing closing `}` brace in `style.css` media query (max-width: 480px)
  that was trapping lightbox, map, filter, and section 11 styles inside it
- Fixed broken JavaScript path casing from `../JS/script.js` to `../js/script.js`
  on `services.html` and `enquiry.html`
- Fixed typo in business name from "Elertical" to "Electrical" on `index.html`
  and `about.html`
- Fixed Google Maps iframe incorrectly placed inside `<form>` tag on `contact.html`
- Fixed radio button validation bug in `script.js` — updated selector from
  `input[name="prop-type"]` to `input[name="property-type"]` to match HTML

### Added
- Added `name` attributes to all contact form fields for Formspree integration
- Added `name` attributes to all enquiry form fields for Formspree integration
- Added Formspree integration to `contact.html` for real email delivery
- Added Formspree integration to `enquiry.html` for real email delivery
- Added `<meta charset="UTF-8">` to `index.html` which was missing
- Added meta description and keywords to `about.html`
- Added meta description and keywords to `enquiry.html`
- Added meta description and keywords to `contact.html`
- Fixed `<title>` tag on `about.html` to include full business name

### Removed
- Removed empty Leaflet map `<div id="map">` from `contact.html`
- Removed Leaflet CSS and JS library links from `contact.html`
- Removed duplicate map on contact page (kept Google Maps iframe only)
- Removed simulated SMTP success block from contact form JS
- Removed simulated success block from enquiry form JS

---

## [Version 3.2] 

### Added
- Added interactive Leaflet map on `contact.html` with marker for
  17 Primrose Street, Kuilsriver
- Added gallery lightbox modal on `services.html` — click images to
  expand with caption display
- Added dynamic service filter buttons on `services.html` (All, 
  Installations, Repairs, Maintenance)
- Added live search input on `services.html` to filter services by keyword
- Added form validation to `enquiry.html` with error messages for all fields
- Added form validation to `contact.html` with error messages
- Added urgency range slider to enquiry form with dynamic label display
- Added success response box on enquiry form submission
- Added simulated SMTP loading response on contact form submission
- Added scroll-to-top animation on successful enquiry submission
- Added section scroll animation using Intersection Observer in `script.js`
- Added Google Maps embed iframe on `contact.html`
- Added responsive mobile breakpoints in `style.css` for 768px and 480px
- Added filter button active state styling in `style.css`
- Added lightbox modal CSS with zoom animation

---

## [Version 3.1]

### Added
- Created initial website structure with 5 pages:
  `index.html`, `about.html`, `services.html`, `enquiry.html`, `contact.html`
- Created `style.css` with BrightSpark brand color scheme
  (dark blue, electric blue, bright yellow)
- Created `script.js` for JavaScript functionality
- Added header with navigation links across all pages
- Added footer with copyright notice across all pages
- Added BrightSpark logo to `index.html`
- Added service listings with images on `services.html`
- Added enquiry form with multiple fieldsets on `enquiry.html`
- Added contact details and social media links on `contact.html`
- Added SEO meta tags (title, description, keywords) to `index.html`
  and `services.html`
- Added responsive viewport meta tag to all pages
- Added CSS custom properties (variables) for consistent theming
- Added image alt-text to all images for accessibility and SEO

## References

* Leaflet, 2026. *Leaflet JavaScript Library Reference*. Available at: [https://leafletjs.com/reference.html](https://leafletjs.com/reference.html).
* MDN Web Docs, 2026. *Document Object Model (DOM) API*. Available at: [https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model).
* OpenStreetMap Foundation, 2026. *OpenStreetMap Copyright and License*. Available at: [https://www.openstreetmap.org/copyright](https://www.google.com/search?q=https://www.openstreetmap.org/copyright).
* W3Schools, 2026. *JavaScript Form Validation*. Available at: [https://www.w3schools.com/js/js_validation.asp](https://www.w3schools.com/js/js_validation.asp).
