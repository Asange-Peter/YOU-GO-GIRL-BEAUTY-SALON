# YOU-GO-GIRL BEAUTY SALON

## Project Overview

**YOU-GO-GIRL BEAUTY SALON** is a multi-page beauty salon website created to present the salon's services, prices, team, contact information and appointment enquiry details.

**Website tagline:** *Your beauty. Your confidence. Your style.*

The project is divided into two main academic sections:

- **Part 1 – HTML:** Website structure, content, navigation, tables, forms, images and embedded map.
- **Part 2 – CSS:** Website presentation, layout, colours, typography, responsive design, forms, tables, buttons, footer and interactive pseudo-classes.

---

# PART 1 – HTML ONLY

## 1.1 HTML Technologies Used

The HTML section uses standard **HTML5** to create the structure and content of the website.

HTML elements used include:

- `<!DOCTYPE html>` for HTML5 document declaration
- `<html>` for the document
- `<head>` for metadata and page information
- `<meta>` for character encoding, viewport and SEO information
- `<title>` for page titles
- `<link>` for connecting the CSS stylesheet
- `<body>` for visible page content
- `<header>` and `<nav>` for website navigation
- `<main>` and `<section>` for page content
- `<h1>`, `<h2>`, `<h3>` and `<h4>` for headings
- `<p>` for paragraphs
- `<a>` for internal navigation and links
- `<img>` for images
- `<ul>` and `<ol>` for lists
- `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>` and `<td>` for tabular information
- `<form>`, `<label>`, `<input>`, `<select>`, `<option>`, `<textarea>` and `<button>` for the enquiry form
- `<iframe>` for the Google Maps location
- `<footer>` for footer information

## 1.2 Website Pages

The website contains five HTML pages.

| Page | File | Purpose |
|---|---|---|
| Home | `index.html` | Introduces the salon and highlights the main beauty areas. |
| About Us | `pages/about.html` | Explains the salon, mission, vision, values and team. |
| Services | `pages/services.html` | Describes the beauty services offered. |
| Prices | `pages/price.html` | Displays the starting price list and pricing information. |
| Contact Us | `pages/contact.html` | Provides contact details, location, FAQs and an appointment enquiry form. |

## 1.3 Home Page – `index.html`

The home page contains:

- Salon name: **YOU-GO-GIRL BEAUTY SALON**
- Tagline: **Your beauty. Your confidence. Your style.**
- Welcome/introduction section
- Salon and beauty-service information
- Beauty areas including hair, nails, lashes, makeup and wigs
- Reasons clients may choose the salon
- A beauty journey/process section
- Links to services, prices and contact pages
- Footer with quick links, social links and contact information

## 1.4 About Us – `pages/about.html`

The About Us page contains:

- Introduction to YOU-GO-GIRL Beauty Salon
- Salon story
- Mission
- Vision
- Core values
- Team information
- Client experience information
- Links to the Services, Prices and Contact pages

### Team

| Team Member | Position | Area of Focus |
|---|---|---|
| Zola Nombona | Manager | Salon operations and team coordination |
| Saneli Peter | CEO | Business leadership and overall direction |
| Thando Thabethe | Receptionist | Client enquiries and front-desk support |
| Kendall Jenner | Stylist | Hair styling and client style support |
| Keith Powers | Stylist | Hair styling and beauty service support |

## 1.5 Services Page – `pages/services.html`

The Services page describes the salon's main beauty categories:

### Hair & Protective Styling

- Hair Wash
- Knotless Braids
- Boho Braids

### Nails & Self-Care

- Manicure
- Pedicure

### Lashes

- Lash Extensions

### Makeup

- Natural Glam
- Full Glam

### Wigs & Hair Products

- Wig options
- Hair products

The page also includes appointment preparation information and links to the price and contact pages.

## 1.6 Price Page – `pages/price.html`

The price page contains the salon's listed starting prices.

| Service | Starting Price |
|---|---:|
| Hair Wash | R100 |
| Lash Extensions | R300 |
| Knotless Braids | R500 |
| Manicure | R250 |
| Pedicure | R200 |
| Boho Braids | R550 |
| Makeup | R500 |

The page explains that final pricing may depend on factors such as:

- Hair length
- Hair density
- Style choice
- Extensions
- Products and materials
- Amount of work required

## 1.7 Contact Page – `pages/contact.html`

The Contact page contains the salon's contact information.

**Email:** yougogirlbeautysalon@gmail.com  
**Phone:** (041)-563 4456  
**Address:** 3 Collett Street, Adcocvale, Gqeberha  
**Hours:** Monday–Friday, 07:00–19:00

It also contains:

- Contact information table
- Mission and vision information
- Appointment enquiry steps
- Google Maps iframe
- Appointment/enquiry form
- Frequently Asked Questions (FAQ)

### Appointment Form Fields

- Full Name
- Email Address
- Phone Number
- Service Interested In
- Preferred Appointment Date
- Preferred Time
- Description of desired look
- Send Enquiry button

## 1.8 Navigation

All pages contain a consistent navigation menu with links to:

- Home
- About Us
- Services
- Prices
- Contact Us

The links use relative paths so that the pages work correctly from the root and `pages` folders.

## 1.9 Images and Assets

Website images are stored inside:

`assets/images/`

Images are used to provide visual examples for hairstyles, nails, lashes and makeup.

Alternative text (`alt`) is included with website images to describe their content.

## 1.10 HTML Structure and Accessibility

The HTML uses semantic elements such as `header`, `nav`, `main`, `section` and `footer` to create a clear document structure.

Accessibility-related HTML features include:

- Descriptive page titles
- Meta viewport settings for mobile devices
- Image `alt` text
- Form labels connected to form controls using `for` and `id`
- Required form fields
- Accessible navigation label using `aria-label`
- Descriptive iframe title

---

# PART 2 – CSS ONLY

## 2.1 CSS File

All website styling is contained in one main stylesheet:

`assets/css/style.css`

The previous separate footer stylesheet has been combined into `style.css`. Therefore, the project uses **one main CSS file** for the website styling.

## 2.2 CSS Organisation

The stylesheet is structured into the following sections:

1. CSS Variables
2. Reset and Default Styles
3. Header and Navigation
4. Main Layout
5. Typography
6. Links and Lists
7. Home/Hero Styling
8. Images
9. Tables
10. Forms
11. Buttons
12. Google Maps / iframe
13. Footer
14. CSS Pseudo-classes
15. Responsive Design – Tablets
16. Responsive Design – Mobile

## 2.3 CSS Variables

The stylesheet uses CSS custom properties (`:root`) for reusable design values, including:

- Primary colours
- Dark and light variations
- Secondary colours
- Accent colour
- Background and surface colours
- Text and muted text colours
- Border colour
- Success and danger colours
- Shadows
- Border radius values
- Transition speed
- Maximum content width

Using variables makes the website easier to maintain because common design values can be changed from one location.

## 2.4 CSS Reset and Default Styling

The stylesheet resets default browser spacing using:

- `margin: 0`
- `padding: 0`
- `box-sizing: border-box`

It also defines default styling for the page, including:

- Font family
- Font size
- Line height
- Letter spacing
- Background
- Text colour
- Smooth scrolling

## 2.5 Header and Navigation Styling

The navigation is styled using:

- Flexbox
- Center alignment
- Flexible wrapping
- Rounded navigation links
- Borders
- Shadows
- Hover effects
- Focus states
- Active states

The header uses a sticky layout on larger screens so that navigation remains available while scrolling.

## 2.6 Main Layout and Sections

The main content uses a centred layout with a maximum width.

Content sections include:

- Rounded corners
- Borders
- Shadows
- Internal spacing
- Decorative top borders
- Hover effects
- Consistent spacing between sections

Alternating section styling is used to improve visual separation.

## 2.7 Typography

The CSS controls:

- Heading sizes
- Heading colours
- Paragraph styling
- List text
- Font weight
- Letter spacing
- Text alignment
- Responsive heading sizes

The main font stack uses Arial and common sans-serif fallbacks.

## 2.8 Links

Links have styling for:

- Normal state
- Hover state
- Visited state
- Keyboard focus

The design uses the salon's primary colour and changes the appearance of links when the user interacts with them.

## 2.9 Images

Images are styled with:

- Maximum width
- Automatic height
- Rounded corners
- Borders
- Shadows
- Object fitting
- Hover scaling effects

Images inside tables receive additional sizing rules to keep them within the layout.

## 2.10 Tables

Tables are used for services, prices, contact information and other structured content.

CSS styling includes:

- Full-width tables
- Borders
- Rounded corners
- Table shadows
- Styled table headings
- Alternating row backgrounds
- Hover effects
- Responsive horizontal scrolling on small screens

## 2.11 Forms

The contact page contains an appointment/enquiry form.

CSS styles the:

- Labels
- Text inputs
- Email inputs
- Telephone inputs
- Date and time inputs
- Select menu
- Textarea
- Required fields
- Valid fields
- Invalid fields
- Focus states

Form controls use consistent spacing, borders, rounded corners and focus effects.

## 2.12 Buttons

The enquiry button uses:

- Rounded pill shape
- Salon primary colour
- White text
- Border
- Shadow
- Hover effect
- Focus state
- Active state
- Disabled state

## 2.13 Google Maps / iframe

The embedded Google Maps iframe is styled to:

- Use the available content width
- Have a minimum height
- Have rounded corners
- Have a shadow
- Remain responsive

## 2.14 Footer Styling

The footer CSS is included directly inside `assets/css/style.css`.

The footer contains three main areas:

1. Salon information
2. Quick navigation links
3. Contact information

Footer styling includes:

- Gradient background
- Accent top border
- White text
- Responsive grid layout
- Social links
- Hover effects
- Footer copyright section

## 2.15 CSS Pseudo-classes

The stylesheet includes multiple pseudo-classes to improve interaction and form feedback.

Examples include:

- `:hover` – changes styling when the pointer is over an element
- `:active` – styles an element while it is being activated
- `:focus` – styles focused form controls
- `:focus-visible` – improves visible keyboard focus
- `:visited` – styles visited navigation links
- `:required` – identifies required form controls
- `:valid` – provides feedback for valid form fields
- `:invalid` – provides feedback for invalid form fields
- `:nth-child()` – supports alternating table row styling
- `:last-child` – controls styling for final elements

## 2.16 Responsive Design

The CSS includes media queries so that the website can adapt to different screen sizes.

### Tablet Layout – up to 768px

At tablet sizes:

- Navigation spacing is reduced
- Main content becomes narrower
- Sections use smaller padding
- Headings become smaller
- Tables use reduced cell padding
- Images and maps are resized
- Footer changes to a two-column layout

### Mobile Layout – up to 480px

At mobile sizes:

- Navigation becomes a vertical column
- Navigation links use the full available width
- Content sections use smaller padding
- Headings are reduced
- Tables can scroll horizontally
- Form controls remain easy to use on mobile
- Buttons become full width
- The footer becomes a single-column layout
- Social links are centred

## 2.17 CSS Design Theme

The website uses a beauty-salon-inspired visual theme based around:

- Pink and burgundy tones
- Soft light-pink backgrounds
- White surfaces
- Gold accent details
- Rounded corners
- Soft shadows
- Smooth transitions

The design is intended to create a modern, welcoming and feminine salon appearance while keeping the content readable.

---

# Repository Structure

```text
YOU-GO-GIRL-BEAUTY-SALON/
│
├── index.html
├── README.md
│
├── pages/
│   ├── about.html
│   ├── services.html
│   ├── price.html
│   └── contact.html
│
└── assets/
    ├── css/
    │   └── style.css
    │
    └── images/
        └── website image assets
```

---

# Website Information

**Business Name:** YOU-GO-GIRL BEAUTY SALON  
**Tagline:** Your beauty. Your confidence. Your style.  
**Email:** yougogirlbeautysalon@gmail.com  
**Phone:** (041)-563 4456  
**Address:** 3 Collett Street, Adcocvale, Gqeberha  
**Opening Hours:** Monday–Friday, 07:00–19:00

---

# Main Beauty Services

- Hair Wash
- Knotless Braids
- Boho Braids
- Manicure
- Pedicure
- Lash Extensions
- Makeup
- Wigs and Hair Products

---

# How to View the Website

1. Open the repository in GitHub.
2. Open `index.html` to view the home page.
3. The remaining HTML pages are located in the `pages` folder.
4. The stylesheet is located in `assets/css/style.css`.
5. Website images are stored in `assets/images/`.

The website is a static HTML/CSS project and does not require a database or JavaScript to display the current content.

---

# Project Summary

This repository demonstrates the development of a complete multi-page salon website using **HTML5 for structure and CSS3 for presentation**.

**Part 1 focuses on HTML only:** structure, content, navigation, images, tables, forms, semantic elements and embedded content.

**Part 2 focuses on CSS only:** visual design, layout, colours, typography, responsive behaviour, forms, tables, buttons, footer styling and pseudo-classes.

The result is a structured, responsive beauty salon website that presents the salon's services, prices, team, contact details and appointment enquiry information in a consistent design.
