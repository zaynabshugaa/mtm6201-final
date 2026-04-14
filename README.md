# mtm6201-final

# Plant Palette - Final Project 

# Figma Link: https://www.figma.com/design/dVbtzc6RiC21UwwkAUlem7/zaynab-shugaa-Plant-Palette?node-id=0-1&t=GjqCGfsnjQmrh0Z7-1


## Project Overview
Plant Palette is a high-fidelity, responsive website designed for a fictional modern vegan restaurant. The project focuses on a "nature-made" aesthetic, using a green and yellow palette to highlight fresh, plant-based dining. This site was developed as the final requirement for MTM6201.

## The Process
My process first began by designing the website and establishing a strong brand identity. I determined the overall feel and look of the website using colours and typography that matched well with the message Plant Platte was putting out. During my coding process I used Bootstrap to ensure that my website worked across all device sizes as well as well as using it for formating certain things on the website. 

## Challenges & Troubleshooting
One of the most significant challenges I faced during development was implementing the responsive `<picture>` element and `srcset` attributes. 

**The Problem:** During testing, images would intermittently disappear when resizing the browser window, particularly in Safari. 
**The Solution:** I overcame this by performing a deep audit of my file naming conventions—removing spaces and capital letters that caused pathing errors. I also implemented a global CSS image reset to ensure that image containers maintained their dimensions during viewport transitions, preventing the containers from collapsing to zero height.

## Key Learnings
Through this project, I deepened my understanding of:
- **Responsive Image Optimization:** The technical requirements of the `<picture>` tag and the importance of precise file pathing.
- **Bootstrap Customization:** Using CSS variables to create a custom brand system on top of a heavy framework.
- **Accessibility:** Ensuring high contrast ratios, semantic header hierarchies, and keyboard-navigable forms.

## Assets & Resources
### Frameworks & Libraries
- **Bootstrap 5** 
- **Hover.css** 
- **Animate.css** 
- **Bootstrap Icons**

### Typography
- **Poppins (Bold):** Headings via Google Fonts.
- **Avenir/Helvetica:** Body text.

### Stock Media Identification
*All stock images used under Creative Commons/Open License. No copyrighted materials were used.*
- **Unsplash:** 
    - `avocados.jpg` (Hero image)
    - `hummus-wrap.jpg` (CTA Section and hero section for menu)
    - `testi-male.jpg` & `testi-girl.jpg` (Testimonials)
    - `about-us.jpg` (Chef image for about us/ourstory)
    - *Note: All menu item images (Rainbow Harvest, Artisan Toast, etc.) are also sourced from Upslash - https://unsplash.com/.*

### Tools Used
- **VS Code** 
- **GitHub Desktop**