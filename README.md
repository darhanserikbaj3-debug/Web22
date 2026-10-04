# Assignment #3: Responsive Web Design

**Student Name:** Serikbai Darkhan  
**Group:** SE-2540  

---

## Overview

A responsive web page ("Cooking Academy") built using **CSS3 Media Queries** and the **Bootstrap 5 12-column Grid System**.

**Breakpoints:**
- **Mobile:** `< 576px`
- **Tablet:** `576px - 991.98px`
- **Desktop:** `>= 992px`

---

## Summary of Work Process

1. **HTML Structure:** Built `main.html` with semantic HTML5 tags, a Bootstrap navbar, section containers, cards, and a footer.
2. **Media Queries:** Styled `style.css` using custom `@media` queries for dynamic typography and flexbox layouts.
3. **Bootstrap Grid:** Integrated Bootstrap 5 grid classes (`col-12`, `col-md-6`, `col-lg-4`, `col-lg-8`) for flexible section layouts.
4. **Navigation:** Implemented a responsive navbar with a mobile hamburger menu toggle.
5. **Testing:** Verified responsiveness across screen sizes using browser DevTools.

---

## Task Breakdown & Implementation

### Part 1. Media Queries

#### Task 0. Responsive Typography
- **Requirement:** Change font sizes dynamically across devices.
- **Implementation:** Custom media queries scale base HTML font size ($14\text{px} \to 15\text{px} \to 16\text{px}$) and heading selectors (`.responsive-heading`, `.responsive-lead`).
- **Screenshots:**
  - *Mobile / Tablet View:*  
    ![perreo](Screenshot 2026-10-04 at 4.31.37 PM.png)
  - *Desktop View:*  
    ![perreo](Screenshot 2026-10-04 at 4.31.50 PM.png)

---

#### Task 1. Responsive Layout with Media Queries
- **Requirement:** 3 boxes in a row on desktop, 2 on tablet, stacked on mobile (pure CSS).
- **Implementation:** Built with CSS Flexbox media queries (`calc(33.333% - 14px)` on desktop, `calc(50% - 10px)` on tablet, `100%` on mobile).
- **Screenshots:**
  - *Mobile View:*  
    ![perreo](Screenshot 2026-10-04 at 4.34.26 PM.png)
  - *Tablet View:*  
    ![perreo](image.png)
  - *Desktop View:*  
    ![perreo](Screenshot 2026-10-04 at 4.34.26 PM.png)

---

### Part 2. Bootstrap Grid System

#### Task 2. Bootstrap Responsive Columns
- **Requirement:** 3 columns (3 equal on desktop, 2+1 on tablet, stacked on mobile).
- **Implementation:** Applied Bootstrap classes `col-12 col-md-6 col-lg-4`.
- **Screenshots:**
  - *Mobile View:*  
    ![perrreo](Screenshot 2026-10-04 at 4.34.26 PM.png)
  - *Tablet View:*  
    ![perreo](Screenshot 2026-10-04 at 4.34.26 PM.png)
  - *Desktop View:*  
    ![perreo](Screenshot 2026-10-04 at 4.34.26 PM.png)

---

#### Task 3. Bootstrap Navigation Bar
- **Requirement:** Navbar with logo, links, and collapsible mobile menu.
- **Implementation:** Used Bootstrap `.navbar`, `.navbar-expand-lg`, and `.collapse` components.
- **Screenshots:**
  - *Mobile View:*  
    ![alt text](image-1.png)
  - *Desktop View:*  
    ![alt text](image-2.png)

---

### Part 3. Combined Project

#### Task 4. Responsive Portfolio Page
- **Requirement:** Page combining header navbar, main grid section (projects + student info sidebar), and footer.
- **Implementation:** Built section `#portfolio` using `col-12 col-lg-8` (projects) and `col-12 col-lg-4` (sidebar).
- **Screenshots:**
  - *Desktop View:*  
    ![alt text](image-4.png)
  - *Mobile/Tablet View:*  
    ![alt text](image-3.png)