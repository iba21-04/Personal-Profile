# Design System & Color Palette

## 🎨 Color Variables

All colors are defined as CSS variables in `css/style.css` for easy customization:

```css
:root {
    /* Primary Colors */
    --accent-pink: #ff006e;       /* Main accent - Neon pink */
    --accent-purple: #c77dff;     /* Secondary - Soft purple */
    --accent-blue: #3a86ff;       /* Tertiary - Bright blue */
    
    /* Background Colors */
    --dark-bg: #0a0e27;           /* Main background */
    --darker-bg: #05070d;         /* Footer/secondary background */
    --card-bg: #1a1f3a;           /* Card backgrounds */
    
    /* Text Colors */
    --text-primary: #e0e0e0;      /* Main text */
    --text-secondary: #a0a0a0;    /* Secondary text */
    --text-muted: #707070;        /* Muted/subtle text */
    
    /* Border Colors */
    --border-color: rgba(255, 0, 110, 0.3);  /* Pink borders with transparency */
    
    /* Glow Effects */
    --glow-pink: 0 0 20px rgba(255, 0, 110, 0.6);
    --glow-purple: 0 0 20px rgba(195, 125, 255, 0.6);
    --glow-blue: 0 0 20px rgba(58, 134, 255, 0.6);
    
    /* Transitions */
    --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}
```

## 📊 Color Usage Guide

### Primary Colors (Use for main actions & accents)
- **Neon Pink (#ff006e)**: 
  - Main headings
  - Primary buttons
  - Active states
  - Border accents
  
- **Purple (#c77dff)**:
  - Hover effects
  - Secondary accents
  - Timeline elements
  - Achievement highlights

- **Bright Blue (#3a86ff)**:
  - Links and tags
  - Icon accents
  - Secondary buttons
  - Tech stack labels

### Background Colors (Layered hierarchy)
- **Dark (#0a0e27)**: Main page background
- **Darker (#05070d)**: Footer, deeper elements
- **Card (#1a1f3a)**: Card and container backgrounds

### Text Colors (Accessibility)
- **Primary (#e0e0e0)**: Main body text, high contrast
- **Secondary (#a0a0a0)**: Descriptions, less important info
- **Muted (#707070)**: Timestamps, subtle information

## 🌈 Color Combinations

### Recommended Color Pairs
```
Pink + Blue = Modern tech feel
Purple + Pink = Warm, friendly energy  
Blue + Green = Calm, professional
Pink + Orange = Creative, energetic
```

## ✨ Glow Effects

The design uses neon glow effects for:
- Button hover states
- Profile picture border
- Card shadows
- Border accents

### How Glows Work
```css
box-shadow: 0 0 20px rgba(255, 0, 110, 0.6);  /* Pink glow */
```

Adjust intensity by:
- **Blur radius** (20px) - Higher = more diffuse
- **Color opacity** (0.6) - Higher = more intense

## 🎯 Using Colors in Custom CSS

### Add Pink Accent
```css
color: var(--accent-pink);
border: 2px solid var(--accent-pink);
box-shadow: var(--glow-pink);
```

### Add Blue Link
```css
color: var(--accent-blue);
border-bottom: 2px solid var(--accent-blue);
```

### Add Purple Hover
```css
:hover {
    color: var(--accent-purple);
    box-shadow: var(--glow-purple);
}
```

## 🔄 Gradient Examples

The design uses several gradients:

### Pink to Purple Gradient
```css
background: linear-gradient(135deg, #ff006e, #c77dff);
```

### Multi-color Gradient
```css
background: linear-gradient(135deg, #ff006e, #c77dff, #3a86ff);
```

### Subtle Background Gradient
```css
background: linear-gradient(135deg, rgba(255, 0, 110, 0.05), rgba(51, 56, 236, 0.05));
```

## 🎨 Alternative Color Schemes

### Dark Purple Theme
```css
--accent-pink: #da70d6;      /* Light purple */
--accent-purple: #a855f7;    /* Medium purple */
--accent-blue: #7c3aed;      /* Dark purple-blue */
```

### Cyberpunk Green
```css
--accent-pink: #0ff;         /* Cyan */
--accent-purple: #f0f;       /* Magenta */
--accent-blue: #0f0;         /* Green */
```

### Minimalist Monochrome
```css
--accent-pink: #ffffff;      /* White */
--accent-purple: #cccccc;    /* Light gray */
--accent-blue: #666666;      /* Dark gray */
--dark-bg: #1a1a1a;          /* Very dark */
```

## 📱 Responsive Color Considerations

Colors remain consistent across all screen sizes. The design uses:
- **Larger touch targets** on mobile with clear color contrast
- **Readable text** with sufficient color contrast ratio (WCAG AA)
- **Consistent accent colors** across all device sizes

## ♿ Accessibility

The color palette meets WCAG AA standards for:
- ✅ Text contrast (4.5:1 for normal text)
- ✅ Large text contrast (3:1 for large text)
- ✅ UI component contrast (3:1 for borders/accents)

### Color Blindness Considerations
The design doesn't rely solely on color to convey information:
- Uses icons and text labels
- Clear text descriptions
- Distinct brightness levels
- Patterns and shapes

## 🎬 Animation Color Effects

### Glow Pulse Animation
```css
@keyframes glow-pulse {
    0%, 100% { opacity: 0.6; transform: scale(1); }
    50% { opacity: 0.8; transform: scale(1.1); }
}
```

### Glitch Effect
Uses three colors with text-shadow:
```css
color: #3a86ff;                    /* Primary */
text-shadow: -2px 0 #ff006e;       /* Secondary */
text-shadow: 2px 0 #c77dff;        /* Tertiary */
```

## 🖌️ Custom Color Creation

To create your own color scheme:

1. **Pick a primary color** (dominant)
2. **Choose a secondary** (complementary)
3. **Add a tertiary** (accent)
4. **Use light/dark variations**
5. **Test contrast ratios**

### Tools for Creating Palettes
- [Coolors.co](https://coolors.co)
- [Adobe Color](https://color.adobe.com)
- [Material Design Colors](https://material.io/design/color)
- [Tailwind Colors](https://tailwindcss.com/docs/customizing-colors)

## 📋 CSS Color Classes

### Text Colors
```css
.text-primary { color: var(--text-primary); }
.text-secondary { color: var(--text-secondary); }
.text-muted { color: var(--text-muted); }
.text-pink { color: var(--accent-pink); }
.text-purple { color: var(--accent-purple); }
.text-blue { color: var(--accent-blue); }
```

### Background Colors
```css
.bg-dark { background: var(--dark-bg); }
.bg-card { background: var(--card-bg); }
.bg-pink-light { background: rgba(255, 0, 110, 0.1); }
.bg-blue-light { background: rgba(58, 134, 255, 0.1); }
```

### Border Colors
```css
.border-pink { border-color: var(--accent-pink); }
.border-purple { border-color: var(--accent-purple); }
.border-blue { border-color: var(--accent-blue); }
```

---

**Remember**: Colors should enhance your personal brand and maintain good readability. Test your choices across different lighting conditions and devices! 🎨
