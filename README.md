# Workshop Booking – UI/UX Enhancement

## Introduction
This repository contains my submission for **Python Screening Task 1**, focused on enhancing the UI/UX of the workshop booking portal.

The original site was functional but minimal. The goal of this enhancement was to improve the overall user experience—especially for students accessing the portal on mobile devices—while keeping the core Django structure intact.

## Table of Contents
- Project Overview
- Task Objective
- Getting Started
- Technical Approach
- UX & Design Reasoning
- Visual Showcase
- Submission Checklist
- Contact & Submission
- License

## Project Overview
This project enhances the Django-based workshop booking portal used by coordinators and instructors.

### Key Goals
- Improve usability and accessibility on small screens
- Refine visual hierarchy and navigation
- Keep the interface lightweight and fast-loading

**Reference Repository:** [FOSSEE/workshop_booking](https://github.com/FOSSEE/workshop_booking)

## Task Objective
- Enhance the look and feel of the existing portal
- Improve readability, navigation, and accessibility
- Ensure mobile-first responsiveness
- Maintain fast load times with minimal dependencies
- Provide a professional, consistent interface

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/FOSSEE/workshop_booking.git
cd workshop_booking
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Apply Database Migrations
```bash
python manage.py migrate
```

### Run Development Server
```bash
python manage.py runserver
```

### Open in Browser
```
http://127.0.0.1:8000/
```

## Technical Approach

### Languages/Tools
- HTML, CSS, JavaScript

### Frameworks
- Bootstrap 5 (responsive layout)
- Material Icons (iconography)

### Enhancements
- Toastr (feedback messages)
- Chart.js (visualization)

### Performance Constraints
- Bootstrap CDN for styling
- Minimal JS libraries (only Chart.js + Toastr)
- Optimized images and static assets
- Avoided heavy animations for smooth performance

## UX & Design Reasoning

### Guiding Principles
- Mobile-first design with Bootstrap grid + custom media queries
- Accessibility (semantic HTML, ARIA roles, keyboard navigation)
- Consistency in colors, buttons, and typography
- Feedback via clear error messages & toast notifications
- Visual hierarchy through spacing, contrast, and structured headings

### Responsiveness Across Devices
- Tested layouts on multiple screen sizes
- Bootstrap utility classes for flexibility
- Custom tweaks for small screens
- Touch-friendly forms, tables, and modals

### Design vs Performance Trade-offs
- Used CDN-hosted Bootstrap for speed
- Restricted libraries to Chart.js + Toastr
- Optimized static assets
- Avoided unnecessary animations

### Biggest Challenge & Solution
- **Challenge:** Making Django templates fully accessible while handling dynamic data.
- **Solution:**
  - Refactored templates with semantic HTML
  - Passed data safely using JSON script tags
  - Added ARIA attributes for accessibility
  - Tested all UI components (charts, paginators, dropdowns) with keyboard navigation and screen readers

## Visual Showcase


### Before vs After
- **Before:**
  - Minimal, non-responsive UI
  - Limited accessibility
  - Basic navigation and feedback
- **After:**
  - Modern, mobile-first design
  - Accessible forms, tables, and navigation
  - Interactive charts and notifications

👉 (If deployed, insert demo link here)

## Submission Checklist
- Clean, readable, well-structured code
- Progressive commits (no "big dump" commits)
- README includes reasoning + setup instructions
- Screenshots / demo included
- Code documented where necessary

## Contact & Submission
- Push updated code to a public GitHub repository
- Share the repository link via email: pythonsupport@fossee.in

## License
This project is submitted as part of the FOSSEE Python Screening Task.
Usage is restricted to evaluation and educational purposes.
