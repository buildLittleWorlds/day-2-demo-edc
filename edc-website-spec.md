# Design Specification: Professional Regional Development Training Site

## 1. Project Overview
**Objective:** Create a training/sandbox website that mirrors the professional aesthetic of a civic economic development organization. The site should feel familiar to staff members of the St. Charles County EDC but remain a distinct "dummy" version for educational purposes.

## 2. Color Palette (Hex Codes)
Maintain a "Civic Professional" theme using high-contrast, authoritative colors.

* **Primary (Civic Navy):** `#004B8D`
    * *Usage:* Header backgrounds, primary buttons, and H1/H2 headings.
* **Secondary (Accent Red):** `#C8102E`
    * *Usage:* Call-to-action (CTA) buttons, news labels, and active navigation states.
* **Neutral Background (Light Grey):** `#F8F9FA`
    * *Usage:* Section backgrounds and card containers.
* **Text (Primary):** `#212529` (Near-Black)
* **Text (Muted):** `#6C757D` (Medium Grey for footers and subtext)

## 3. Typography
Use a clean, dual-sans-serif approach to balance modern industry with traditional governance.

* **Heading Font:** `Montserrat, sans-serif`
    * *Style:* Bold (700+) for main titles. Use `text-transform: uppercase` and `letter-spacing: 0.05em` for top-level navigation.
* **Body Font:** `Open Sans, sans-serif` or `Roboto, sans-serif`
    * *Style:* Normal weight (400). Set `line-height: 1.6` for optimal readability in long-form training content.

## 4. Visual Styles & UI Components

### Header & Navigation
* **Structure:** Sticky header with a white background. 
* **Utility Bar:** A thin top bar (approx. 30px) in `#F8F9FA` for social links or secondary links.
* **Nav Links:** Navy text (`#004B8D`), transitioning to Red (`#C8102E`) on hover.

### Cards & Containers
* **Background:** White (`#FFFFFF`).
* **Borders:** A 3px top-border using the Primary Navy (`#004B8D`). No side or bottom borders.
* **Shadows:** Subtle elevation: `box-shadow: 0 4px 6px rgba(0,0,0,0.05)`.
* **Border Radius:** Professional 4px rounding on all corners.

### Buttons
* **Primary:** Solid Navy (`#004B8D`) with White text.
* **Secondary/CTA:** Solid Red (`#C8102E`) with White text.
* **Shape:** Rectangular with a 4px border-radius. Use `text-transform: uppercase` and `font-weight: 600`.

## 5. Layout Guidelines
* **Grid System:** Use a standard 12-column grid. 
* **Spacing:** Use generous padding (approx. 60px - 80px) between major vertical sections to create a clean, modern feel.
* **Footer:** Dark Navy background with light grey text. Include a 3-column layout for "Quick Links," "Contact Info," and "Social Media."

## 6. Training Environment Modifications
To ensure this is clearly a "Sandbox" environment:
* Add a subtle, fixed-position badge or watermark in the bottom corner labeled "TRAINING MODULE."
* Replace specific corporate logos with generic "Regional Development" icons or text-based placeholders.