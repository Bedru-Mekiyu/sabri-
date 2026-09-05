# Sebrin Akmel - Portfolio Website

A responsive, professional portfolio website showcasing work experience, skills, services, and project achievements. Built using modern HTML5, CSS3, JavaScript, and Bootstrap.

## 📌 Project Overview

This repository contains the source code and assets for **Sebrin Akmel's personal portfolio website**. Designed to highlight professional milestones, technical expertise, creative services, and career achievements in a clean, modern aesthetic.

---

## ✨ Key Features

- **Responsive Layout**: Designed for seamless viewing across mobile, tablet, and desktop screens using Bootstrap 5.
- **Hero & Intro Section**: Interactive dynamic typing header displaying key roles and titles.
- **About & Statistics**: Highlights professional background, skills, and key statistics.
- **Interactive Portfolio Gallery**: Showcases recent works with category filtering and lightboxes (via GLightbox).
- **Services Overview**: Details core service offerings and consulting options.
- **Contact Form**: Integrated contact section powered by PHP and AJAX for client inquiries.

---

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, SCSS, JavaScript (ES6)
- **Framework**: Bootstrap 5
- **Icons & Fonts**: Bootstrap Icons, Google Fonts (Roboto, Ubuntu, Nunito)
- **Libraries**:
  - [AOS](https://michalsnik.github.io/aos/) (Animate On Scroll)
  - [GLightbox](https://biati-digital.github.io/glightbox/)
  - [Swiper](https://swiperjs.com/)
  - [Typed.js](https://mattboldt.github.io/typed.js/)
  - [Isotope Layout](https://isotope.metafizzy.co/)
  - [PureCounter](https://github.com/SreeragRaajan/PureCounter-v2)

---

## 📁 Repository Structure

```text
├── index.html              # Main homepage & portfolio page
├── portfolio-details.html  # Detailed view page for individual portfolio items
├── service-details.html    # Detailed view page for individual service offerings
├── starter-page.html      # Template starter layout
├── forms/                  # Contact form handler (PHP/AJAX)
│   └── contact.php
└── assets/                 # Static assets directory
    ├── css/                # Compiled CSS files
    ├── js/                 # JavaScript logic & dynamic features
    ├── scss/               # SCSS source files
    ├── img/                # Website images & portfolio assets
    └── vendor/             # Third-party libraries (Bootstrap, AOS, Swiper, etc.)
```

---

## 🚀 Getting Started

### Prerequisites

To run this portfolio locally, you only need a modern web browser. For processing the PHP contact form, a local server environment with PHP support (e.g., Apache, Nginx, XAMPP, or Live Server) is recommended.

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/portfolio.git
   cd portfolio
   ```

2. **Serve locally**:
   - For simple frontend development, open `index.html` directly in your browser or use VS Code Live Server.
   - To test PHP contact form functionality locally, run PHP's built-in web server:
     ```bash
     php -S localhost:8000
     ```
     Then navigate to `http://localhost:8000` in your browser.

---

## ⚙️ CI/CD & Quality Assurance

This repository includes continuous integration workflows using **GitHub Actions**:
- Automated verification of HTML markup integrity.
- Verification of asset and folder structure.

---

## 📜 License & Acknowledgments

- Built upon template design elements provided by [BootstrapMade](https://bootstrapmade.com/).
- Licensed under standard template terms (see template header disclosures).
