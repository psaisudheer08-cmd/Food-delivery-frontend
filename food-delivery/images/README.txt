# FoodieExpress - Image Assets Guide
========================================

Welcome! This folder contains all the placeholder images used across the
FoodieExpress food delivery website.

All placeholder files are currently clean, lightweight SVG files so that
the website looks complete and colorful right out of the box, with zero
external dependencies or broken image links.

------------------------------------------------------------------------
HOW TO REPLACE THESE WITH YOUR OWN PHOTOS (JPG / PNG):
------------------------------------------------------------------------
When you want to use real food photos (e.g., from Unsplash, Pexels, or
your own camera):

1. Save your photo into this `images/` folder (for example: `pizza.jpg`).
2. Open `index.html` in VS Code or any text editor.
3. Find the matching `<img>` tag and update the `src` attribute:
   Example:
     Change: <img src="images/dish-pizza.svg" alt="...">
     To:     <img src="images/dish-pizza.jpg" alt="...">
4. Keep the `alt` text accurate and descriptive for accessibility.

------------------------------------------------------------------------
IMAGE SPECIFICATIONS & RECOMMENDED DIMENSIONS:
------------------------------------------------------------------------

1. HERO BANNER
   - File: `hero-food.svg`
   - Used in: Hero section at the top of the home page
   - Recommended Size: 800 x 600 px (Landscape)
   - Suggested Content: A vibrant feast with pizza, burger, and drinks.

2. CATEGORY ICONS (At least 6)
   - Files:
     * `category-pizza.svg`   -> Pizza Category
     * `category-burger.svg`  -> Burger Category
     * `category-biryani.svg` -> Biryani Category
     * `category-dessert.svg` -> Desserts Category
     * `category-chinese.svg` -> Chinese Category
     * `category-drinks.svg`  -> Drinks & Beverages Category
   - Recommended Size: 300 x 300 px (Square or circular avatar)
   - Suggested Content: Focused shot or graphic of each food category.

3. POPULAR DISHES (At least 6)
   - Files:
     * `dish-pizza.svg`   -> Margherita Basil Pizza
     * `dish-burger.svg`  -> Classic Crispy Cheese Burger
     * `dish-biryani.svg` -> Dum Hyderabadi Chicken Biryani
     * `dish-brownie.svg` -> Sizzling Choco Fudge Brownie
     * `dish-noodles.svg` -> Veg Hakka Chilli Garlic Noodles
     * `dish-shake.svg`   -> Alphonso Mango Thick Shake
   - Recommended Size: 600 x 400 px (3:2 ratio)
   - Suggested Content: Appetizing close-up shots of individual plated dishes.

4. RESTAURANTS (At least 4)
   - Files:
     * `restaurant-biryani.svg` -> Royal Biryani House
     * `restaurant-pizza.svg`   -> The Oven Story Pizza Co.
     * `restaurant-burger.svg`  -> Burger Junction & Grill
     * `restaurant-chinese.svg` -> Golden Dragon Wok
   - Recommended Size: 600 x 380 px (Landscape)
   - Suggested Content: Restaurant storefront, ambiance, or signature platter.

5. HOW IT WORKS ICONS (3 Steps)
   - Files:
     * `step-choose.svg` -> Step 1: Browse your favorite food
     * `step-order.svg`  -> Step 2: Place fast contactless order
     * `step-enjoy.svg`  -> Step 3: Fast delivery at your doorstep
   - Recommended Size: 160 x 160 px (Square icon)

Tip: For fast loading, compress your JPG/PNG files using https://tinypng.com
before adding them to your project!
