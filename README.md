# Capstone-Naman-Gupta-Lab-5

# SkillSphere — Online Learning Platform (Capstone Project)

**Theme:** Online Learning Platform  
**Student:** Naman Gupta
**Course:** B.Tech Computer Science (Data Science)

This is a responsive landing page for an online learning platform called **SkillSphere**.  
It is built using **HTML5** and **CSS3** only, following the capstone project requirements.

---

## Features Implemented

### Layout & Structure
- Semantic HTML5 tags: `header`, `nav`, `main`, `section`, `article`, `aside`, `figure`, `footer`.
- Clear structure:
  - Hero banner with primary CTA.
  - “Why choose us” feature section.
  - Courses grid with cards.
  - Visual filters sidebar.
  - Pricing plans section.
  - Testimonials section.
  - Contact form.

### Online Learning Requirements
- **Course cards:**  
  Each card shows course title, level, duration, short description, tags (skills) and buttons for “View details” and “Enroll”.
- **Testimonials:**  
  Three learner testimonials using `figure` and `blockquote` for semantic quotes.
- **Pricing:**  
  Three tiers – Starter (Free), Pro Student, Team/Campus – matching a real platform.
- **Contact form:**  
  Includes fields for Name, Email, Topic, Course of interest, and Message with proper `<label>` elements.

### Responsiveness
- Uses **CSS Flexbox** and **Grid** for layout.
- Two main breakpoints:
  - **Desktop:** width ≥ 1024px (three-column grids).
  - **Tablet:** up to 1023px (two-column grids).
  - **Mobile:** up to 600px (single-column layout, stacked header/nav).
- Relative units and CSS variables for consistent spacing and typography.

### Visual & UX
- Consistent color palette via CSS custom properties (`--accent`, `--bg`, etc.).
- Card shadows and hover/ focus effects on buttons and course cards.
- Floating animation on the hero illustration using `@keyframes heroFloat`.
- Sticky header with a subtle glassmorphism effect.
- “Skip to main content” link for accessibility.
- Descriptive `alt` attributes for images.

---

## File Structure

```text
project-folder/
├─ index.html
├─ style.css
└─ images/
   ├─ logo-placeholder.png
   ├─ hero-online-learning.jpg
   ├─ course-web-dev.jpg
   ├─ course-data-science.jpg
   └─ course-uiux.jpg
