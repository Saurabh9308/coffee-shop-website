# ☕ Coffee House Landing Page (SPA)

## 📌 Project Overview

This project is a **Single-Page Application (SPA) / Landing Page** designed for a **Coffee House / Café**. The website focuses on delivering a visually appealing, responsive, and user-friendly experience using modern front-end web technologies.

| Attribute                  | Details                                                                                                       |
| -------------------------- | ------------------------------------------------------------------------------------------------------------- |
| **Project Type**           | Single-Page Application (SPA) / Landing Page                                                                  |
| **Business Type**          | Coffee House / Café                                                                                           |
| **Location Focus**         | Berdorf, Germany (mentioned in the About section)                                                             |
| **Core Technologies**      | HTML5, CSS3, JavaScript                                                                                       |
| **Key External Libraries** | Font Awesome (Icons), Swiper.js (Carousel)                                                                    |
| **Design Philosophy**      | Responsive layout with a clean UI, using a rich primary color `#3b141c` and a warm secondary accent `#f3961c` |

---

## 💻 Key Sections and Functionality

The website is structured into clearly defined sections to ensure intuitive navigation and an engaging user experience.

---

### 1. Header and Navigation (`<header>`)

* **Sticky Navigation Bar**
  The navbar is fixed at the top of the viewport (`position: fixed;`), allowing users to navigate between sections at any time.

* **Mobile Menu (Off-Canvas)**
  A slide-out mobile navigation menu is implemented for smaller screens.
  The menu visibility is controlled using JavaScript by toggling the `show-mobile-menu` class.

* **Smooth Scrolling**
  Smooth transitions between sections are enabled using:

  ```css
  html {
    scroll-behavior: smooth;
  }
  ```

---

### 2. Hero Section

* **Purpose**
  Acts as the primary welcome section, featuring bold typography and impactful visuals.

* **Call-to-Action (CTA)**
  Includes two clearly defined buttons:

  * **Order Now** – Primary action
  * **Contact Us** – Secondary action
    Both buttons include subtle hover transitions for improved interactivity.

---

### 3. About Section

* **Content**
  Introduces the coffee house, its location in **Berdorf, Germany**, and its commitment to delivering a premium coffee experience.

* **Visual Design**
  Features a large, circular image (`about-image.jpg`) to create a modern and focused visual presentation.

* **Social Media Links**
  Integrated icons linking to:

  * Facebook
  * Instagram
  * Twitter

---

### 4. Menu Section

* **Layout**
  Displays six main product categories using a grid-style layout:

  * Hot Beverages
  * Cold Beverages
  * Refreshment
  * Special Combos
  * Dessert
  * Burger & Fresh Fries

* **Design Approach**
  Uses contrasting colors (light text on a dark background) to ensure strong visual emphasis and readability.

---

### 5. Testimonials Section

* **Carousel Functionality**
  Implemented using **Swiper.js**, providing a smooth, touch-enabled slider for customer reviews.

* **Features**

  * Navigation arrows (previous / next)
  * Pagination dots for quick navigation
  * Responsive behavior across devices

---

### 6. Gallery Section

* **Visual Presentation**
  A grid layout showcasing six images highlighting the café’s products and ambiance.

* **Hover Interaction**
  Images include a subtle zoom-in effect on hover:

  ```css
  transform: scale(1.3);
  ```

  This enhances user engagement without overwhelming the layout.

---

### 7. Contact Section

* **Contact Information**

  * Address
  * Email
  * Phone number
  * Detailed operating hours

* **Contact Form**
  Includes input fields for:

  * Name
  * Email
  * Message
    The form is styled with clean input elements and a clear submit button for usability.

---

### 8. Footer Section

* **Content**

  * Copyright
  * Social media links
  * Policy links (Privacy Policy, Refund Policy)

* **Layout**
  Uses a clean, space-between alignment to maintain a professional and balanced appearance.

---

## 📱 Responsive Design

The entire website is fully responsive and optimized for:

* Desktop
* Tablet
* Mobile devices

Media queries and flexible layouts ensure consistent usability across all screen sizes.

---

## 🚀 Technologies Used

* **HTML5** – Semantic structure
* **CSS3** – Layout, animations, and responsiveness
* **JavaScript** – Interactivity and mobile menu handling
* **Font Awesome** – Iconography
* **Swiper.js** – Testimonials carousel

