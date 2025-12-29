# Custom Website Styles (WP Elementor + CSS)

This repository contains the **custom CSS styles (and HTML snippets)** from a Wordpress Elementor project developed for a client in the Hospitality Industry.

It serves three main purposes:
1. **Backup & Version Control** -to make sure I don’t lose my work if Elementor resets or overrides styles.
2. **Demonstration** -  to showcase proper front-end code with BEM naming conventions, mobile-first styling, and clear structure.
3. **Scalability** - keeps a clean naming convention and global tokens for consistent design across multiple pages.

## 📁 Structure
- `css/base.css` → root variables, resets, global typography
- `css/sidebar-layout.css` → helpers for the unique sidebar-layout
- `css/components.css` → reusable UI elements (buttons, footer, etc.)
- `css/overrides.css` → snippets that override Elementor's basic css rules
- `css/utilities.css` → Utility classes that mimic tailwind functionality 
- `css/pages/`  
  - `booking.css` → reservation page
  - `contact.css` → contact details and inquiry form
  - `document-pages.css` → contact details and inquiry form
  - `guestbook.css` → guest reviews/testimonials
- `css/section-stylings/` → css files containing stylings for specific repeated sections
- `htlml/pages/` → HTML snippets for custom HTML elements built for the page, sorted by page where they appear

## 🔧 Conventions
- **Mobile-first**, using media queries for larger screens
- **BEM naming convention** for clarity and scalability (`block__element--modifier`)  
- **CSS variables** (`:root { --color-primary: #2a7a47; }`) for colors, spacing, typography

## 🚀 Backup Guide (for web agency responsible for maintenance)
1. Clone this repository
2. Upload HTML snippets into pages through Elementor's Custom HTML blocks
2. Upload contents of 'BACKUP_site_settings.css' into Elementor's Site Settings/Custom CSS panel

## 📄 License
This repo is open-source under the MIT License.