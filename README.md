# Navrouz and Juma Celebration Card

## Overview
This is an interactive, animated HTML greeting card created to celebrate the dual occasion of Navrouz (Persian/Central Asian New Year) and Juma (Friday). The card features beautiful animations, interactive elements, and a responsive design that works across different devices.

## Features
- **Animated Background**: Gradient background with subtle color shifts
- **Interactive Elements**: 
  - Parallax effect on mouse movement (when implemented)
  - Interactive blessing button with animation on click
  - Hover effects on various elements
- **Decorative Elements**:
  - SVG flower decorations in corners
  - Animated floating particles
  - Tulip illustration
  - Ornamental dividers
- **Responsive Design**: Adapts to different screen sizes (desktop, tablet, mobile)
- **Beautiful Typography**: Combination of Dancing Script for headings and Poppins for body text
- **Celebration Message**: Written in Uzbek language

## Technical Details
- **Languages**: HTML, CSS, JavaScript
- **External Libraries**:
  - Animate.css (via CDN) for animations
  - Google Fonts (Poppins, Dancing Script)
- **Browser Compatibility**: Modern browsers (Chrome, Firefox, Safari, Edge)
- **Responsive Breakpoints**:
  - Desktop: 768px and above
  - Tablet: 481px to 768px
  - Mobile: 480px and below

## How to Use
1. Download all the files or copy the HTML code into a file with `.html` extension
2. Open the file in any modern web browser
3. The card will display with animations automatically playing
4. Interact with the card by:
   - Moving your mouse to see parallax effects (when JavaScript is completed)
   - Clicking the blessing button to trigger celebration effects

## Customization
You can easily customize this card by:

- **Changing Colors**: Modify the CSS variables in the `:root` selector
  ```css
  :root {
      --primary-color: #2c7a2c;
      --secondary-color: #8bc34a;
      --accent-color: #ff7043;
      --highlight-color: #d63384;
      --light-color: #f9f7f1;
      --gold-color: #ffd700;
  }
  ```
- **Updating Text**: Replace the message content in the HTML
- **Modifying Animations**: Adjust timing and effects in the CSS `@keyframes` rules
- **Changing Flower Designs**: Modify the SVG paths and colors

## JavaScript Functions (Note: Some appear incomplete)
The script includes:
- `createParticles()`: Generates floating flower symbols
- `createParticle()`: Creates individual particles
- `createCelebrationParticles()`: Generates celebration effects when blessing is clicked
- `parallaxEffect()` and `moveGlowEffect()`: Referenced but not fully implemented in the provided code

## Language
The greeting card text is in Uzbek language, celebrating Navrouz (spring new year) and Juma (Friday).

## Notes
- Some JavaScript functions appear to be referenced but not fully implemented in the provided code (parallaxEffect, moveGlowEffect)
- The code includes preparation for additional interactive features that would need to be completed

## License
This code can be freely used and modified for personal use.
