# Amazon Clone

## Project Overview

This project is a front-end replica of Amazon's website, focused on recreating its navigation bar, hero section, shopping categories, and footer. The design mimics the core elements of the Amazon homepage, providing a simplified version to explore basic HTML, CSS, and layout principles.

### Features:

1. **Navigation Bar**: Includes Amazon's logo, delivery location, search bar, sign-in option, orders, and cart section.
2. **Hero Section**: Displays a hero banner with a message, giving an experience similar to Amazon's international shopping offer.
3. **Shopping Categories**: Various boxes showcasing categories such as Clothes, Electronics, Health, Beauty, etc., styled to replicate the category sections on the Amazon homepage.
4. **Footer Section**: Consists of useful links like "Careers", "Returns Center", and "Account," along with social media and legal notices.

---

## Project Structure:

### HTML:

- The HTML file is structured into semantic sections: 
  - `header`: For the navigation bar.
  - `div.hero-section`: To contain the hero banner.
  - `div.shop-section`: For the shopping categories in boxes.
  - `footer`: To replicate Amazon's comprehensive footer.

### CSS:

- The CSS file is designed to style each section following the Amazon style guide:
  - **Colors**: Main colors like `#0f1111` (blackish background), `#222f3d` (darker footer sections), and `#007185` (links).
  - **Layout**: Flexbox is used heavily for aligning items horizontally and vertically in various sections like the navbar, search bar, and footer.
  - **Responsive Design**: The site layout is responsive and adjusts to different screen sizes.

---

## Project Breakdown

### 1. Navigation Bar:
- Consists of the Amazon logo (placeholder), location option, search bar, sign-in option, returns/orders, and shopping cart.
- CSS: Flexbox used for alignment, with hover effects on each section. The search bar has a custom width, background color, and border-radius for rounded edges.
  
### 2. Hero Section:
- Displays a banner at the top with a promotional message.
- The background image is customizable, and the hero message is in a white box that stands out against the image.

### 3. Shopping Categories:
- Each category is displayed in a separate box with a background image for visual representation.
- CSS: The boxes are styled with padding, margin, and responsive width to fit multiple categories on larger screens, with `flex-wrap` ensuring a responsive layout.

### 4. Footer:
- Divided into multiple sections:
  - Top link "Back to Top"
  - Useful links about Amazon, selling on Amazon, and customer service
  - Amazon logo and legal sections.
  
- CSS: Multiple layers of background colors and consistent font sizes/styles for a professional look, matching the Amazon footer.

---

## How to Run the Project

### 1. Clone the Repository:
```bash
git clone https://github.com/PradeepTiwarii/Amazon-Clone.git
```

### 2. Open the Project:
Open the HTML file (`index.html`) in any modern web browser to view the project. Ensure that all image and CSS paths are correct relative to your folder structure.

### 3. File Structure:

```
/Amazon-Clone
│
├── index.html       # Main HTML file.
├── style.css        # CSS styles for the project.
├── images/          # Folder to store images (like logo, hero image, category images).
│   ├── amazon_logo.png
│   ├── hero_image.jpg
│   └── box1_image.jpg, box2_image.jpg ... (category images)
└── README.md        # This readme file.
```

### 4. External Resources:
- **FontAwesome**: Used for icons (like cart, magnifying glass, and location icon) via CDN.
- **Google Fonts**: Used for font styling, particularly for the Amazon-like text styles.

---

## Customization:

1. **Images**: Replace the `background-image` in the CSS with your desired images for each category or the hero section.
2. **Colors**: Modify the colors in the CSS file to fit your branding or theme.
3. **Text**: Update text in the `index.html` file to suit your content, such as category names, messages, and footer links.

---

## Credits:
This project uses open-source libraries like:
- **FontAwesome** for icons.
- **Google Fonts** for fonts.

All images are placeholders and should be replaced with appropriate images. This project is for educational purposes and should not be used for commercial purposes without proper licensing.

---

### License:

This project is licensed under the MIT License. Feel free to use, modify, and distribute the project.
