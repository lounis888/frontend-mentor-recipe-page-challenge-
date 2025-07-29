# frontend-mentor-recipe-page-challenge-
this is a repository for a small project of a recipe page on the Frontend Mentor site. this is the first time i did a project, the first time on github, so feel free to guide me
README.template
# Recipe Page - Omelette Master

A beautifully designed, responsive recipe page for a classic omelette, showcasing modern CSS techniques and semantic HTML structure.

![Recipe Page Screenshot](![alt text](file:///c%3A/Users/anyone/Downloads/2025-07-29_21-28-03.png))

## Table of Contents

- [Overview](#overview)
  - [Project Goals](#project-goals)
  - [Features](#features)
- [Implementation Details](#implementation-details)
  - [HTML Structure](#html-structure)
  - [CSS Techniques](#css-techniques)
  - [Responsive Design](#responsive-design)
- [Development Process](#development-process)
  - [Key Learnings](#key-learnings)
  - [Challenges Solved](#challenges-solved)
- [Future Improvements](#future-improvements)
- [Resources](#resources)
- [Author](#author)

## Overview

### Project Goals
- Create an aesthetically pleasing recipe page with proper hierarchy
- Implement responsive design for all device sizes
- Ensure accessibility through semantic HTML
- Use modern CSS features for layout and styling

### Features
- Responsive layout with mobile (375px) and desktop (1440px) breakpoints
- Custom typography with Google Fonts (Young Serif and Outfit)
- Nutrition information table with styled values
- Preparation time section with distinctive styling
- Section dividers for clear content separation
- Print-friendly design


## Implementation Details

### HTML Structure
```html
<section class="ingredients">
  <h2>Ingredients</h2>
  <ul>
    <li>2-3 large eggs</li>
    <!-- More ingredients -->
  </ul>
</section>

<section class="instructions">
  <h2>Instructions</h2>
  <ol>
    <li><strong>Beat the eggs:</strong> In a bowl...</li>
    <!-- More steps -->
  </ol>
</section>

<section class="nutrition">
  <h2>Nutrition</h2>
  <table class="nutrition-table">
    <tr>
      <td>Calories</td>
      <td class="nutrition-value">277kcal</td>
    </tr>
    <!-- More nutrition data -->
  </table>
</section>

# css-techniques
```CSS
/* Custom font implementation */
body {
  font-family: 'Young Serif', Georgia, serif;
}

/* Responsive breakpoints */
@media (max-width: 1440px) {
  .recipe-card {
    padding: 20px;
  }
}

/* Nutrition table styling */
.nutrition-table tr {
  border-bottom: 1px solid #e8e8e8;
}

.nutrition-value {
  color: #854632;
  font-weight: bolder;
}

/* Preparation time section */
.prep-time {
  background-color: hsl(30, 18%, 87%);
  border-radius: 20px;
  padding: 25px;
}

### Responsive Design
- **Mobile (375px)**: 
  - Increased padding for touch targets
  - Simplified layout structure
  - Optimized font hierarchy for small screens
- **Tablet**:
  - Adjusted grid layouts
  - Scaled typography for mid-sized viewports
- **Desktop (1440px)**:
  - Max-width container with comfortable reading line-length
  - Strategic whitespace utilization
- Fluid typography using `rem` units
- Flexible images maintaining aspect ratios

### Development Process
#### Key Learnings
1. **CSS Variable Implementation**: Created theme consistency with HSL color values
2. **Responsive Typography**: Mastered relative units for accessible scaling
3. **Flexbox Layout**: Centered card component with `justify-content: center`
4. **Table Styling**: Enhanced data presentation with border control
5. **Media Queries**: Implemented device-specific adaptations

#### Challenges Solved
- **Image Scaling**: Used `max-width: 100%` for responsive images
- **Vertical Rhythm**: Established consistent spacing with margin/padding system
- **Color Accessibility**: Verified contrast ratios for readability
- **List Customization**: Styled markers with `::marker` pseudo-element
- **Print Optimization**: Ensured content integrity in print media

### Future Improvements
- 🌙 Dark mode using CSS variables
- ⏱️ Interactive cooking timer
- 🔢 Serving size calculator
- ⭐ Recipe rating system
- 📱 Social sharing functionality
- 🖨️ Dedicated print stylesheet

### Resources
- [Google Fonts](https://fonts.google.com/) - Typography
- [Frontend Mentor](https://www.frontendmentor.io) - Design inspiration
- [CSS-Tricks](https://css-tricks.com/) - Layout techniques
- [MDN Web Docs](https://developer.mozilla.org/) - HTML/CSS reference
- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) - Accessibility

Author
Mohamed Bennai
Frontend Mentor Profile
