# Custom Website Styles (WP Elementor + CSS)

This repository contains the **custom CSS styles (and perhaps other code snippets)** from a Wordpress Elementor project developed for a client in the Hospitality Industry.

It serves three main purposes:
1. **Backup & Version Control** -to make sure I don’t lose my work if Elementor resets or overrides styles.
2. **Demonstration** -  to showcase proper front-end code with BEM naming conventions, mobile-first styling, and clear structure.
3. **Scalability** - keeps a clean naming convention and global tokens for consistent design across multiple pages.

## 📁 Structure (will change while progressing with the site)
- `css/base.css` → root variables, resets, global typography
- `css/layout.css` → global layout helpers (flex/grid utilities, spacing, containers)
- `css/components.css` → reusable UI elements (buttons, nav, sidebar, etc.)
- `css/pages/`  
  - `homepage.css` → WP front-page
  - `domes.css` → highlights the type of stay my client offers
  - `gallery.css` → photography gallery of the place
  - `guestbook.css` → guest reviews/testimonials
  - `about.css` → about the team and the environment
  - `booking.css` → reservation page
  - `services.css` → introduction for the extra services the parent company offers
  - `contact.css` → contact details and inquiry form

## 🔧 Conventions
- **Mobile-first**, using media queries for larger screens
- **BEM naming convention** for clarity and scalability (`block__element--modifier`)  
- **CSS variables** (`:root { --color-primary: #2a7a47; }`) for colors, spacing, typography

## 🚀 Usage
1. Clone this repository.  
2. Apply the custom classes/IDs inside Elementor as needed.
2. Upload relevant CSS into Elementor "Custom CSS" or the main CSS located inside site settings

## 📄 License
This repo is open-source under the MIT License.