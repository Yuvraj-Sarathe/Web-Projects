# Certification Projects

freeCodeCamp Responsive Web Design certification projects - deployed and production-ready.

**Main Portfolio:** https://Yuvraj-Sarathe.github.io/Web-Projects/

---

## 0. Technical Documentation Page ✅

**Status:** Completed & Deployed  
**Completion Date:** December 15, 2025  
**Deployment Date:** December 15, 2025

### Description
A comprehensive technical documentation page serving as a complete portfolio showcase. This project demonstrates advanced CSS layout techniques, fixed navigation, responsive design, and professional presentation of technical content across multiple programming domains.

### Technologies
- HTML5 (Semantic structure, accessibility, document architecture)
- CSS3 (Advanced layouts, animations, gradients, responsive design)

### Key Features
- 📑 Fixed sidebar navigation with smooth scroll behavior
- 📱 Fully responsive design (mobile, tablet, desktop breakpoints)
- 🎨 Modern CSS gradients, box-shadows, and pseudo-elements
- 💻 Custom code blocks with syntax styling
- 🔲 Complex grid layouts for skills and connection buttons
- 🎯 Project showcase sections with hover effects
- ⚡ Smooth transitions and professional animations
- 🌐 Multi-section technical portfolio (Web Dev, Java, Python, C++, Skills)
- ♿ Semantic HTML5 structure with proper heading hierarchy

### Content Sections
1. **Introduction** - Personal overview and technical focus
2. **Web Development** - HTML/CSS projects with live demos
3. **Java Development** - Hangman game with ANSI colors
4. **Python Projects** - Connect4 (Pygame/NumPy) and GUI games
5. **C++ Programming** - Tic-Tac-Toe with Windows console colors
6. **Skills & Tech Stack** - Comprehensive technology overview
7. **Connect With Me** - Professional links with styled buttons

### Technical Highlights
```css
/* Fixed Navigation with Smooth Scroll */
#navbar {
    position: fixed;
    backdrop-filter: blur(10px);
}

html {
    scroll-behavior: smooth;
}

/* Gradient Code Blocks */
code {
    background: linear-gradient(135deg, #1e293b 0%, #0f172a 100%);
    border-left: 4px solid #667eea;
}

/* Project Showcase Hover Effects */
.project-showcase:hover {
    transform: translateX(5px);
    box-shadow: 0 8px 20px rgba(102, 126, 234, 0.15);
}

/* Skills Grid Layout */
.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
}
```

### Responsive Design
- **Desktop (>815px):** Fixed sidebar navigation, wide content area
- **Tablet/Mobile (≤815px):** Collapsible navigation, single-column layout
- **All Devices:** Optimized typography, touch-friendly buttons

### Design Philosophy
Unlike typical documentation pages, this project combines technical reference material with portfolio presentation, showcasing both frontend development skills and the ability to document complex technical work professionally.

### View Project
- **🔗 Live Demo:** https://Yuvraj-Sarathe.github.io/Web-Projects/Projects/Documentation%20Project/
- **📁 Source Code:** index.html | style.css | Documentation

---

## 1. Survey Form ✅

**Status:** Completed & Deployed  
**Completion Date:** November 29, 2025  
**Deployment Date:** December 9, 2025

### Description
A modern, responsive survey form featuring glassmorphism design with beautiful gradient backgrounds and smooth animations. Built with pure HTML5 and CSS3, showcasing advanced styling techniques and responsive design principles.

### Technologies
- HTML5 (Semantic structure, form validation)
- CSS3 (Modern styling, animations, gradients)

### Key Features
- 🎨 Glassmorphism UI with backdrop blur effects
- 🌈 Beautiful gradient backgrounds (purple to pink spectrum)
- ✅ HTML5 form validation with visual feedback
- 📱 Fully responsive design (mobile-first approach)
- 🎭 Custom styled form elements (inputs, selects, checkboxes, radio buttons)
- ⚡ Smooth transitions and hover effects
- 🔒 Input validation states (valid/invalid visual indicators)
- ♿ Accessibility considerations (labels, semantic HTML)

### Technical Highlights
```css
/* Glassmorphism effect */
background: rgba(255,255,255,0.1);
backdrop-filter: blur(10px);

/* Gradient background */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Validation states */
input:invalid:not(:focus) {
    border-color: #ff6b6b;
}

input:valid:not(:placeholder-shown) {
    border-color: #51cf66;
}
```

### Responsive Design
- **Desktop:** Optimal viewing experience with centered form (60vw, max 500px)
- **Tablet:** Adapts smoothly with maintained aspect ratio
- **Mobile:** Fully functional on small screens with adjusted padding

### View Project
- **🔗 Live Demo:** https://Yuvraj-Sarathe.github.io/Web-Projects/Projects/Survey%20Form/
- **📁 Source Code:** [index.html](./Survey%20Form/index.html) | [style.css](./Survey%20Form/style.css)

---

## 2. Tribute Page ✅

**Status:** Completed & Deployed  
**Completion Date:** December 8, 2025  
**Deployment Date:** December 9, 2025

### Description
A comprehensive tribute page honoring Terry A. Davis, the brilliant programmer who single-handedly created HolyC programming language, TempleOS operating system, its compiler, kernel, and bootloader. The page explores his technical achievements, his struggles with mental illness, and his lasting impact on the programming community.

### Technologies
- HTML5 (Semantic structure, accessibility)
- CSS3 (Advanced styling, animations, responsive design)

### Key Features
- 📖 Comprehensive narrative structure (Introduction → Creation → Struggles → Legacy)
- 🎨 Modern gradient backgrounds and card-based layout
- 🖼️ Multiple images with smooth hover zoom effects
- 🌈 Custom gradient text highlighting for technical terms
- 📱 Fully responsive design with mobile-optimized layouts
- 🔗 External links to Wikipedia and Wikimedia Commons
- ⚡ Smooth transitions and hover effects throughout
- 🎯 Social media links footer (GitHub, LinkedIn, LeetCode)
- ♿ Semantic HTML5 with proper document structure

### Content Sections
1. **Introduction:** Context comparing Terry to Linus Torvalds, Ritchie, and Thompson
2. **The Creation:** 
   - HolyC Programming Language
   - TempleOS - The Third Temple
3. **Struggles and Legacy:** His mental health journey and lasting impact

### Technical Highlights
```css
/* Gradient text effect */
.highlight {
    background: linear-gradient(120deg, #ffd89b 0%, #19547b 100%);
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

/* Image hover effect */
img:hover {
    transform: scale(1.05);
    transition: transform 0.3s ease;
}

/* Card sections */
#intro, #creation, #death {
    background-color: white;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
```

### Responsive Design
- **Desktop:** Multi-column layouts with optimized reading width (max 1000px)
- **Tablet (768px):** Adjusted font sizes and padding
- **Mobile (480px):** Single column, stacked layouts, optimized typography

### View Project
- **🔗 Live Demo:** https://Yuvraj-Sarathe.github.io/Web-Projects/Projects/Tribute%20Page/
- **📁 Source Code:** [index.html](./Tribute%20Page/index.html) | [style.css](./Tribute%20Page/style.css)

---

## 3. Product Landing Page ✅

**Status:** Completed & Deployed  
**Completion Date:** December 24, 2025  
**Deployment Date:** December 24, 2025

### Description
A futuristic marketing landing page for the fictional "Zenith G1" quantum personal computer. This project demonstrates advanced HTML/CSS techniques, form submission handling, modal dialogs, responsive pricing tables, and production-grade deployment with email integration.

### Technologies
- HTML5 (Semantic structure, forms, modals)
- CSS3 (Glassmorphism, gradients, animations, responsive design)
- JavaScript (Modal dialogs, scroll functions, form interaction)
- FormSubmit.co (Form-to-email service)

### Key Features
- 🎯 Hero section with email capture form
- 📧 Real form submission to email via FormSubmit.co
- 🎨 Feature showcase cards with hover effects
- 🖼️ Image gallery with overlay animations
- 💰 Pricing comparison table (3 tiers)
- 🔲 Modal dialogs (Privacy, Terms, Contact)
- ⚡ Smooth scroll to email input from pricing buttons
- 📱 Fully responsive design
- 🎭 Glassmorphism UI with backdrop blur
- 🌈 Gradient backgrounds and text effects

### Technical Highlights
```javascript
// Scroll to email input when pricing button clicked
function scrollToEmail(button) {
    const allCards = document.querySelectorAll('.pricing-card');
    allCards.forEach(card => card.classList.remove('featured'));
    button.closest('.pricing-card').classList.add('featured');
    document.getElementById('hero').scrollIntoView({ behavior: 'smooth' });
    setTimeout(() => {
        document.getElementById('email').focus();
    }, 500);
}

// Modal dialog system
function openModal(modalId) {
    document.getElementById(modalId).style.display = 'flex';
    document.body.style.overflow = 'hidden';
}
```

### Form Submission Flow
1. User enters email in hero section
2. Form submits to FormSubmit.co with hidden fields
3. FormSubmit forwards email to inbox
4. User redirected to thank-you.html
5. Auto-response sent to user

### Responsive Design
- **Desktop (>768px):** Full-width hero, 3-column layouts, side-by-side form
- **Mobile (≤768px):** Stacked layouts, vertical form, single-column cards

### View Project
- **🔗 Live Demo:** https://Yuvraj-Sarathe.github.io/Web-Projects/Projects/Product%20Landing%20Page/
- **📁 Source Code:** [index.html](./Product%20Landing%20Page/index.html) | [style.css](./Product%20Landing%20Page/style.css)
- **📖 Full Documentation:** [README.md](./Product%20Landing%20Page/README.md)

---

## 4. Personal Portfolio Webpage ⏳

**Status:** Not Started  
**Expected Completion:** January 2026

---

## 🎯 Development Standards

All projects in this collection follow professional web development best practices:

### Code Quality
- ✅ Semantic HTML5 elements
- ✅ Clean, organized CSS with logical structure
- ✅ Meaningful class and ID names
- ✅ Consistent formatting and indentation
- ✅ Well-commented code where necessary

### Accessibility
- ✅ Proper heading hierarchy (h1 → h2 → h3)
- ✅ Alt text for all images
- ✅ Form labels properly associated
- ✅ Keyboard navigation support
- ✅ Sufficient color contrast

### Responsive Design
- ✅ Mobile-first approach
- ✅ Fluid layouts with flexible units (%, vw, em, rem)
- ✅ Media queries for breakpoints
- ✅ Tested on multiple screen sizes
- ✅ Touch-friendly interactive elements

### Performance
- ✅ Optimized images
- ✅ Minimal external dependencies
- ✅ Clean, efficient CSS
- ✅ Fast load times

---

## 🚀 Deployment

All projects are deployed using **GitHub Pages**, providing:
- ✅ Free hosting
- ✅ Automatic HTTPS
- ✅ Fast global CDN delivery
- ✅ Easy updates via Git push

**Main Portfolio:** https://Yuvraj-Sarathe.github.io/Web-Projects/

---

## 📊 Progress Tracking

**Projects Completed:** 4 / 5  
**Chronological Order:**
1. Survey Form (Nov 29, 2025)
2. Tribute Page (Dec 8, 2025)
3. Technical Documentation (Dec 15, 2025)
4. Product Landing Page (Dec 24, 2025)

**Portfolio Display Order:**
- Project 0: Technical Documentation (Portfolio showcase)
- Project 1: Survey Form
- Project 2: Tribute Page
- Project 3: Product Landing Page

**Modules Completed:** 11+ freeCodeCamp lessons  
**Deployment:** Production-ready, publicly accessible  
**Code Quality:** Portfolio-grade

---

**Last Updated:** December 24, 2025