# Ira Batra - Personal Portfolio Website

## Overview
A modern, responsive, dark-themed portfolio website for a Computer Engineering student. The design features neon pink, purple, and blue accents with smooth animations, hover effects, and micro-interactions throughout.

## 🎨 Design Features

### Visual Design
- **Dark Theme**: Deep navy/black background (#0a0e27) with elegant contrast
- **Neon Accents**: 
  - Primary Pink: #ff006e
  - Secondary Purple: #c77dff
  - Tertiary Blue: #3a86ff
- **Glowing Effects**: Soft glow shadows and neon highlights
- **Modern Typography**: Clean sans-serif font with gradient text effects
- **Smooth Animations**: Floating particles, glitch effects, and smooth transitions

### Interactive Elements
- Animated navigation bar with gradient underlines
- Smooth scroll behavior with active link highlighting
- Hover effects on all interactive elements
- Floating particles in hero section
- Glitch effect on main heading
- Profile picture with pulse glow animation
- Expandable/interactive cards with shadow effects
- Animated input fields with glow effects
- Scroll-to-top button that appears when scrolling down

## 📱 Responsive Design
- **Desktop**: Full multi-column layouts with side-by-side content
- **Tablet** (768px): Adjusted grid layouts and font sizes
- **Mobile** (480px): Single column layouts, mobile-optimized navigation

## 📚 Sections

### 1. **Home**
- Welcome section with animated hero text
- Profile picture with glow effect
- Call-to-action buttons for navigation
- Floating particle background effects

### 2. **About Me**
- Personal bio and introduction
- Four skill categories:
  - Programming Languages
  - Web & Mobile Development
  - Hardware & Embedded Systems
  - Tools & Frameworks
- Hover-interactive skill tags

### 3. **Work Experience**
- Timeline-based layout with vertical gradient line
- Four work experiences (SFU Robot Soccer, Algo Communications, Mathnasium, Starbucks)
- Each with:
  - Job title and company name
  - Location and date range
  - Key bullet points
  - Hover animations

### 4. **Projects**
- 9-project grid showcasing:
  - RISC-V CPU Pipeline Simulator
  - 2D Java Game
  - Road Rhythm Car Stereo System
  - Campus Cravings Mobile App
  - Reaction Timer Game
  - Digital Alarm Clock System
  - AST & File System Implementation
  - PCB Soldering Project
  - Cyber Safety Website
- Each project card includes:
  - Icon and title
  - Description
  - Tech stack tags
  - Hover effects with glow

### 5. **Education & Achievements**
- SFU Computer Engineering degree information
- Two major achievements (awards)
- Four extracurricular activities
- All with hover effects and icons

### 6. **Contact**
- Interactive contact form with:
  - Name field
  - Email field
  - Message textarea
  - Animated input focus states
  - Form validation
- Social links (GitHub, LinkedIn, Email)
- Success/error notifications

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic structure
- **CSS3**: Advanced styling with:
  - CSS Variables for theming
  - Flexbox and CSS Grid
  - Animations and transitions
  - Gradient backgrounds
  - Media queries for responsiveness
- **JavaScript**: Interactive features
  - Smooth scrolling
  - Form validation
  - Hamburger menu toggle
  - Scroll-to-top functionality
  - Intersection Observer for animations
  - Notification system

### Design Tools/Concepts
- Glassmorphism effects
- Neon aesthetic
- Micro-interactions
- Smooth animations
- Accessibility considerations

## 📂 File Structure
```
Personal-Profile/
├── index.html          # Main single-page website
├── css/
│   └── style.css      # Comprehensive styling
├── js/
│   └── script.js      # Interactive functionality
└── profile.jpg        # Profile picture (to be added)
```

## 🚀 Getting Started

### Installation
1. Clone or download the repository
2. Add your profile picture as `profile.jpg` in the root directory
3. Update contact information in the contact section:
   - Email link in the contact section
   - GitHub and LinkedIn URLs

### Local Development
1. Open `index.html` in a modern web browser
2. No build process or dependencies required
3. All CSS and JavaScript are self-contained

### Customization

#### Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --accent-pink: #ff006e;
    --accent-purple: #c77dff;
    --accent-blue: #3a86ff;
    --dark-bg: #0a0e27;
    /* ... other variables */
}
```

#### Fonts
Change the font-family in the `body` selector:
```css
body {
    font-family: 'Your Font Here', sans-serif;
}
```

#### Content
- Edit section content directly in `index.html`
- Update project descriptions, dates, and skills
- Modify experience entries and achievements

## 🌐 Browser Compatibility
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ✨ Special Features

### Animations
- **Glitch Effect**: Main heading with color separation
- **Floating Particles**: Animated particles in hero section
- **Glow Pulse**: Profile picture with pulsing border glow
- **Smooth Transitions**: All interactive elements
- **Scroll Animations**: Elements fade in on scroll

### Interactive Elements
- Hamburger menu for mobile
- Smooth internal linking
- Form validation with error messages
- Hover effects on cards and buttons
- Active navigation highlighting

### Accessibility
- Semantic HTML structure
- Clear color contrast
- Keyboard navigation support
- Responsive design for all devices

## 📝 Notes

- The website is a single-page application (no separate pages)
- All content is integrated into one smooth-scrolling experience
- The contact form currently shows a notification (no backend integration)
- To implement actual form submission, integrate with a backend service (e.g., Formspree, EmailJS)

## 🎯 Future Enhancements

Potential additions:
- Dark/Light theme toggle
- Blog section
- Case studies with images
- Video portfolio section
- Live chat integration
- Backend form processing
- Blog/articles section
- Download resume functionality
- Language selector

## 📄 License
This portfolio website is personal property and should not be redistributed without permission.

## 👤 Author
**Ira Batra**
- Computer Engineering Student at SFU
- Email: [your.email@example.com]
- GitHub: [your-github]
- LinkedIn: [your-linkedin]

---

Built with ✨ passion, designed with 💜 love, powered by 💻 code.
