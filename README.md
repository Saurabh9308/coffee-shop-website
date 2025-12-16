##☕️ Project Overview| Attribute | Details |
| --- | --- |
| **Project Type** | Single-Page Application (SPA) / Landing Page |
| **Business Type** | Coffee House/Café |
| **Location Focus** | Berdorf, Germany (Mentioned in the About section) |
| **Core Technologies** | HTML5, CSS3, JavaScript |
| **Key External Libraries** | Font Awesome (Icons), Swiper.js (Carousel) |
| **Design Philosophy** | Responsive, with a clean layout and a color palette featuring a rich primary color (`#3b141c`) and a warm secondary accent (`#f3961c`). |

---

##💻 Key Sections and FunctionalityThe website is structured with all essential content organized into distinct, easily navigable sections:

###1. Header and Navigation (`<header>`)* **Sticky Navbar:** The navigation bar is fixed to the top of the screen (`position: fixed;`), allowing users to jump between sections quickly.
* **Mobile Menu:** Implements a slide-out, off-canvas menu for smaller screens, managed by toggling the `show-mobile-menu` class using JavaScript.
* **Smooth Scrolling:** The `html { scroll-behavior: smooth; }` property ensures that clicking on navigation links scrolls the user smoothly to the targeted section.

###2. Hero Section* **Focus:** Acts as the main welcome screen with large, impactful imagery and typography.
* **Call to Action (CTA):** Features two distinct buttons: "**Order Now**" (primary action) and "**Contact Us**" (secondary action), with subtle hover transitions.

###3. About Section* **Content:** Provides an introduction to the business, its location, and its dedication to an exceptional coffee experience.
* **Visuals:** Features a large, circular image (`about-image.jpg`) for a modern, focused visual element.
* **Social Links:** Includes links to Facebook, Instagram, and Twitter accounts.

###4. Menu Section* **Layout:** Uses a grid-like layout to showcase six main product categories:
* Hot Beverages
* Cold Beverages
* Refreshment
* Special Combos
* Dessert
* Burger & Fresh Fries


* **Design:** Uses contrasting colors (white text on a dark background) to make the menu items stand out.

###5. Testimonials Section* **Functionality:** Leverages the **Swiper.js** library to create a dynamic, touch-enabled carousel for displaying customer reviews.
* **Features:** Includes navigation arrows (`swiper-button-prev`/`next`) and pagination dots for easy browsing of feedback.

###6. Gallery Section* **Visual Appeal:** A grid of six images showcasing the shop's products and atmosphere.
* **Interactivity:** Implements a subtle zoom-in effect (`transform: scale(1.3);`) on image hover to enhance engagement.

###7. Contact Section* **Information:** Displays essential contact details, including address, email, phone number, and detailed operating hours.
* **Form:** Includes a basic contact form for name, email, and message, styled with clean inputs and a submit button.

###8. Footer Section* **Information:** Contains copyright, links to social media, and policy links (Privacy and Refund).
* **Layout:** Maintains a clean, space-between layout for a professional finish.
