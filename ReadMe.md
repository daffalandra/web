# CV Web Page Documentation

This document provides an overview of the structure and components of the CV web page for Muhammad Daffa Alandra. The page is built using HTML, CSS, Bootstrap, and Font Awesome.

---

## Table of Contents
- [General Overview](#general-overview)
- [Header Section](#header-section)
- [Navigation](#navigation)
- [Main Content Sections](#main-content-sections)
  - [About Me](#about-me)
  - [Contact Information](#contact-information)
  - [Skills](#skills)
  - [Experience](#experience)
  - [Education](#education)
- [Footer](#footer)
- [Custom Styling](#custom-styling)
- [External Dependencies](#external-dependencies)

---

## General Overview

- **Language:** HTML5
- **Character Set:** UTF-8
- **Viewport:** Responsive, optimized for mobile and desktop (`meta` tags included for responsiveness).
- **Styles:** Google Fonts (Roboto), Bootstrap for layout and components, Font Awesome for icons.
- **Custom CSS:** Inline `style` tag for additional design features.

---

## Header Section

The header contains the following components:
- **Profile Picture:** Displayed as a circular image using `object-fit` and `border-radius`.
- **Name and Title:** Muhammad Daffa Alandra's name, position as a Computer Science student, and specialization in IoT.
- **Social Icons:** Links to LinkedIn and GitHub, using Font Awesome icons.

### Header Specific Styles:
- Background: `#007bff` (Bootstrap primary blue).
- Text Color: White.
- Responsive profile picture and headings.

---

## Navigation

A horizontal navigation menu links to various sections of the page:
- **About Me**
- **Contact**
- **Skills**
- **Experience**
- **Education**

Each link scrolls smoothly to its respective section using HTML anchor tags and CSS scroll behavior.

---

## Main Content Sections

The main content is wrapped inside a flex container. It consists of five sections:

### About Me
- A brief introduction about Muhammad Daffa Alandra and his current focus in IoT and Computer Science.

### Contact Information
- Lists contact details like **Email**, **Phone**, and **Location** with corresponding Font Awesome icons.
  
### Skills
- Displays various technical skills with progress bars to indicate proficiency.
- Technologies include:
  - C/C++
  - Python
  - Java
  - HTML/CSS
  - JavaScript
  - Android

### Experience
- A brief paragraph summarizing the work on IoT and mobile app development projects.

### Education
- Lists educational background:
  - **Binus University** (2022 - Present)
  - **SMAN 5 Bandung** (2019 - 2022)

Each educational entry is presented in a hoverable card with subtle animation (scales up slightly on hover).

---

## Footer

The footer includes:
- **Copyright Information:** Displays © 2024 Muhammad Daffa Alandra.
- **Back to Top Link:** Smooth scrolls to the top of the page.

---

## Custom Styling

1. **Font Family:** Roboto (via Google Fonts).
2. **Background Color:** The body has a light grey background `#e9ecef`.
3. **Flexbox Layout:** The `.main-container` uses flexbox for centering the content.
4. **Custom Animations:** Subtle hover animations on the education cards (`transform: scale(1.02)`).
5. **Progress Bars:** Styled with Bootstrap and custom width percentages based on skill levels.

---

## External Dependencies

### Fonts
- Google Fonts: Roboto (`https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap`)

### Icons
- Font Awesome: Provides social media icons and other visual cues (`https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css`)

### Bootstrap
- Bootstrap v5.0 for grid and utility classes (`css/bootstrap.min.css` and `js/bootstrap.bundle.min.js`)

---

## Responsive Design

The page is responsive, adapting to different screen sizes using Bootstrap’s grid system and media queries:
- On larger screens (min-width 768px), the layout adjusts to a row format.
- Typography and spacing are also adjusted for better readability on different devices.

---

## Future Improvements
- **Dynamic Content:** Adding dynamic features like collapsible sections or AJAX-loaded content.
- **SEO Optimization:** Use `meta` tags for better SEO.
- **Form Integration:** Add a contact form for direct communication.
