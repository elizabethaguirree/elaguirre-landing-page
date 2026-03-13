# STANDARDS.md

## BAIS:3300 - Digital Product Management · Module 8 | Personal Landing Page Project

This file contains technical instructions for this project. Every time you
begin a coding session, ask your LLM to read this file before writing any code.

---

## 1. Project Overview

This project is a personal professional landing page for Elizabeth Aguirre, a Business Analytics & Information Systems and Marketing student at the University of Iowa graduating in May 2026. The site is designed to provide recruiters and hiring managers with a clear overview of her skills, projects, and professional experience in a clean, professional format. Success is defined by creating a simple, polished single-page website that highlights analytics and marketing capabilities and directs visitors to LinkedIn, GitHub, and contact information.

---

## 2. Technical Standards

These rules apply to every file in this project.

### Languages

- HTML5 using semantic elements (`header`, `main`, `section`, `footer`, `nav`)
- CSS3
- No inline styles
- No `<style>` tags inside HTML

### Folder structure
/elaguirre-landing-page
├── index.html
├── /css
│ └── stylesheet.css
├── /images
│ └── headshot.jpg
### Architecture

- Static site
- Single `index.html`
- External stylesheet only
- Images stored locally in `/images`
- No backend code
- No database
- Do not link to or embed a resume anywhere on the site

### Responsiveness

- Fully responsive
- Must work from **320px screen width and larger**
- No horizontal scrolling

### Accessibility (WCAG 2.2 Level AA)

- All images must include alt text
- Logical heading hierarchy (`h1 → h2 → h3`)
- Descriptive link text
- Accessible color contrast
- Keyboard navigable links

### Compatibility

Site must render correctly on:

- Chrome
- Safari
- Firefox
- Mobile devices

### Security

External links must use:
target="_blank" rel="noopener noreferrer"
---

## 3. Design Standards

### Color palette

| Role | Color |
|-----|-----|
| Background | #F8F9FA |
| Primary Text | #212529 |
| Accent | #0D6E6E |
| Secondary Background | #E9ECEF |

Clean, minimal, professional look.

### Typography

Font: **Inter (Google Fonts)**

Body text:
- 16px
- Line height: 1.6

Headings:
- H1: 1.8rem bold
- H2: 1.3rem bold

### Imagery

- One professional headshot only
- No stock images
- No emojis

### Layout

- Maximum content width: **800px**
- Centered layout
- Sticky top navigation
- Sections spaced with **60px padding**
- Single column layout on mobile

### Components

**Profile photo**
- Circular crop
- 160px diameter
- Centered in hero section

**Skill tags**
- Rounded pill badges
- Accent background color
- White text

**Contact links**
- LinkedIn
- GitHub
- Email

All links must open in new tabs.

### Tone

The page should feel:

- Professional  
- Approachable  
- Data-driven  

Writing style should be **first person**, confident, and concise.
