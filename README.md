# Workshop Booking – UI/UX Enhancement Submission

## Project Overview
This project is a Django-based workshop booking portal for coordinators and instructors. The goal of this enhancement was to improve the user experience and interface design, especially for students accessing the site on mobile devices, while keeping the core structure intact.

---

## Task Objective
Enhance the look and feel of the basic website, focusing on:
- Readability and navigation on small screens
- Visual hierarchy and user flow
- Fast load times and accessibility

---

## Design Principles & Reasoning
### 1. What design principles guided your improvements?
- **Mobile-first design:** All layouts and components are optimized for mobile screens using Bootstrap 5 and custom media queries.
- **Accessibility:** Semantic HTML, ARIA roles, and keyboard navigation are implemented for all interactive elements.
- **Visual hierarchy:** Clear headings, color contrast, and spacing guide users through the site.
- **Consistency:** Unified color palette, button styles, and iconography (Material Icons) for a professional look.
- **Feedback:** Toastr notifications and clear error messages provide instant feedback.

### 2. How did you ensure responsiveness across devices?
- Used Bootstrap 5 grid and utility classes for flexible layouts.
- Added custom media queries for fine-tuned mobile adjustments.
- Tested navigation, forms, and tables on various screen sizes.
- Ensured all buttons, dropdowns, and modals are touch-friendly and accessible.

### 3. What trade-offs did you make between the design and performance?
- Chose Bootstrap CDN for fast, reliable styling without heavy custom CSS.
- Limited use of external JS libraries to Chart.js and Toastr for essential interactivity.
- Optimized images and static assets for quick load times.
- Avoided excessive animations to maintain performance on low-end devices.

### 4. What was the most challenging part of the task and how did you approach it?
- **Challenge:** Making legacy Django templates fully accessible and interactive, especially with dynamic data and template tags in JS.
- **Approach:** Refactored templates to use semantic HTML, added ARIA attributes, and handled empty data gracefully. Used JSON script tags for safe JS data passing. Debugged and tested all interactive elements (charts, paginator, profile dropdown) for keyboard and screen reader accessibility.

---

## Visual Showcase
### Before & After Screenshots
- **Before:** ![Before Screenshot](docs/before_screenshot.jpg)
- **After:** ![After Screenshot](docs/after_screenshot.jpg)

> For a live demo, see: [your deployed site link here]

---

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/FOSSEE/workshop_booking.git
   cd workshop_booking
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```
4. **Run the development server:**
   ```bash
   python manage.py runserver
   ```
5. **Access the site:**
   Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.

---

## Submission Checklist
- Code is readable and well-structured
- Git history shows progressive work (no single commit dumps)
- README includes reasoning answers and setup instructions
- Screenshots or live demo link included
- Code is documented where necessary

---

## Contact & Submission
- Push your code to a public GitHub repository
- Share the repo link with us via email: pythonsupport@fossee.in

---

__NOTE__: For more details, see `docs/Getting_Started.md`.

---

> We value authentic work. Submissions that appear AI-generated, copied, or templated will be disqualified. Please ensure your work is original, well-documented, and demonstrates thoughtful design.

---
