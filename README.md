# Product Gallery Slider with Swiper

This project implements a responsive product gallery slider using Swiper.js. It includes a main image slider with navigation thumbnails.

## Features
- Fully responsive design.
- Swiping support for mobile devices.
- Thumbnail navigation for the main slider.
- Easy to integrate and customize.

## Requirements
- HTML, CSS, and JavaScript knowledge.
- Swiper.js library (v9 or higher recommended).

## Installation
1. Download or clone the repository.
2. Include Swiper.js in your project:
   - Add the Swiper CSS and JS files to your `index.html`:
     ```html
     <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@9/swiper-bundle.min.css" />
     <script src="https://cdn.jsdelivr.net/npm/swiper@9/swiper-bundle.min.js"></script>
     ```

## Usage
1. Include the HTML structure:
   ```html
   <div class="product-gallery">
       <div class="swiper-container main-slider">
           <div class="swiper-wrapper">
               <div class="swiper-slide"><img src="image1.jpg" alt="Product Image 1"></div>
               <div class="swiper-slide"><img src="image2.jpg" alt="Product Image 2"></div>
               <div class="swiper-slide"><img src="image3.jpg" alt="Product Image 3"></div>
           </div>
       </div>
       <div class="swiper-container thumbnail-slider">
           <div class="swiper-wrapper">
               <div class="swiper-slide"><img src="image1.jpg" alt="Thumbnail 1"></div>
               <div class="swiper-slide"><img src="image2.jpg" alt="Thumbnail 2"></div>
               <div class="swiper-slide"><img src="image3.jpg" alt="Thumbnail 3"></div>
           </div>
       </div>
   </div>



This `README.txt` provides a comprehensive guide to implementing a Swiper product gallery slider, including installation, usage, and customization instructions.
