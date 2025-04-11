# mtm6201-final

# Pawsitive Futures Final Project

## About the Project

This website was created as the final project for the User Experience Design course. The goal was to take my existing high-fidelity wireframes and build a fully functional and responsive website using the Bootstrap framework.

The site represents a fictional animal rescue organization called **Pawsitive Futures**, dedicated to helping pets find homes, educating the public, and supporting surrender and volunteer programs.

---

## Process & Development

The design started with, and was structured around three key content areas: adoption/animals, involvement, and education. Using Bootstrap’s grid system made layout management more efficient, and utility classes helped speed up spacing, responsiveness, and alignment.

The layout includes:
- A responsive 4-column animal section
- Three equally tall info columns below
- A form and surrender section combined for vertical balance
- A pinned footer that remains visible even on short content pages

Semantic HTML, alt text for images, and accessible form labels were all included to meet accessibility standards.

---

## Challenges & Solutions

**1. Layout balance**  
The hardest part was ensuring that all three bottom columns remained equal in height while stacking different types of content. I resolved this using Bootstrap’s `d-flex`, `flex-column`, and `h-100` utilities, keeping everything inside one consistent box per column.

**2. Footer visibility**  
 The footer floated incorrectly due to uneven content heights. Adding `flex-grow` on the main element and a proper `min-height` layout fixed this issue.

**3. Image organization**  
Ensuring that all images loaded correctly required strict file naming and consistent folder structure (`images/` directory). I also used placeholder images temporarily to maintain layout during development.

---

## What I Learned

- How to break down complex mockups into clean, reusable components.
- Better use of Bootstrap's grid and utility classes to create balanced layouts.
- How to debug layout issues by inspecting structure and applying flexbox concepts.
- The value of semantic naming and separating content into visual and structural layers.

---

## External Assets & Resources

The following assets were not created by me and are credited accordingly:

### Frameworks / Libraries
- [Bootstrap 5](https://getbootstrap.com/) – CSS framework used for layout and styling
- [Google Fonts – Dynapuff](https://fonts.google.com/specimen/Dynapuff) – Primary font used across headings and body text

*Note: Notation taken from imdac and https://getbootstrap.com/docs/4.0/utilities/spacing/ bootstrap website notation page

### Placeholder Images
All stock images were used temporarily or replaced with royalty-free animal images for demonstration purposes.


`rabbit.jpg`    
`lizard.jpg`      
`surrender.jpg`   
`volunteer.jpg`    
`dogs.jpg`, `cats.jpg`, `reptiles.jpg`, `birds.jpg` 

*Note: the Images were collected from the stock site https://www.pexels.com and the logo was generated from dall-e

---

## Folder Structure

