# Portfolio Website – Naeche Chukwuemeka

This is my personal portfolio site built as part of the HTML5 & CSS3 assignment.  
It demonstrates semantic HTML, responsive CSS without frameworks, accessibility best practices, and GitHub Pages deployment.


## 🌐 Website Structure

The portfolio contains **four main pages**:

1. **Home (`index.html`)**
   - Introduces me and provides a hero section with a short welcome.
   - Includes a call-to-action button linking to the About page.

2. **About (`about.html`)**
   - Contains my photo and a short **introduction video** (45–60 seconds).
   - Video uses a `poster` image and HTML5 `<video>` with `<source>` fallback and accessibility attributes.

3. **Projects (`project.html`)**
   - Showcases 4–5 projects with headings and short descriptions.
   - Includes responsive project “cards” styled consistently across viewports.

4. **Contact (`contact.html`)**
   - Provides a contact form with **HTML5 validation**:
     - `required` fields
     - `type="email"` for email
     - `type="tel"` with pattern for phone number
   - Includes a footer with my email and copyright notice.

---

## 🎨 Design & Styling

- **CSS Files**  
  - `base.css`: shared global styles  
  - `mobile.css`: for screens up to 600px  
  - `tablet.css`: for 601px–992px  
  - `laptop.css`: for 993px and above  

- **Responsive Design**
  - Implemented using **fluid layouts** and **separate CSS files per viewport** (no Flexbox/Grid).
  - Layout adjusts across mobile, tablet, and laptop viewports.

- **Color Scheme**
  - Selected using **Adobe Color**.  
  - Palette includes dark navy, orange accent (`#f97316`), and white/gray for text and backgrounds.

- **Gradients**
  - **Linear gradient** used in the header and footer backgrounds.  
  - **Angled gradient** applied in the hero section background.  
  - These choices add depth and meet assignment requirements.

- **Buttons**
  - Styled with a hover effect and adjusted for accessibility (contrast fixes applied).

---

## 🎥 Media

- **About Page Video**
  - `<video>` element includes `poster` and multiple `<source>` formats for fallback.
  - Uses `aria-labelledby` to connect the video with its heading.
  - Provides text fallback for unsupported browsers.

---

## ♿ Accessibility

- Semantic HTML: `<header> <nav> <main> <footer>` used consistently.
- Navigation labeled with `aria-label="Primary"`.
- Current page links marked with `aria-current="page"`.
- Video labeled with `aria-labelledby`.
- Form fields associated with `<label>` elements.
- Decorative icons/images marked with `alt=""` or `aria-hidden="true"`.
- Site tested with **WAVE WebAIM** and adjustments made to fix:
  - Redundant link issues
  - Label typos in form
  - Button contrast ratio

---

## ✅ Validation

- All **HTML pages** tested with [W3C HTML Validator](https://validator.w3.org/).
- All **CSS files** tested with [W3C CSS Validator](https://jigsaw.w3.org/css-validator/).
- Accessibility tested using [WAVE WebAIM](https://wave.webaim.org/).

---

## 🚀 Deployment

The site is hosted on **GitHub Pages**:  
👉 [https://naeche-c.github.io/portfolio/](https://naeche-c.github.io/portfolio/)

---

## 📌 Notes

- No external libraries, frameworks, or Flexbox/Grid were used (as per assignment rules).  
- All code was written by me, following examples from Weeks 1–4 lecture slides.  
- Any external references (≤10% code) were cited in code comments.

