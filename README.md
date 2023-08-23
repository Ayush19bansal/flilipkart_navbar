# Hosted link https://ayush19bansal.github.io/flilipkart_navbar/
# UI
![image](https://github.com/Ayush19bansal/flilipkart_navbar/assets/118842033/0194c1e7-ea2c-416d-9a41-8b1b7db32515)

# HTML
![image](https://github.com/Ayush19bansal/flilipkart_navbar/assets/118842033/47603877-0904-434c-b53b-af143b5fbf87)
![image](https://github.com/Ayush19bansal/flilipkart_navbar/assets/118842033/fb0d0b8b-9ed9-4397-bd37-c09a2e147276)
This HTML code represents a webpage header and a section containing links to various categories. Here's a brief explanation:

1. **Header Section (`header class="navbar-top"`)**: This is the top section of the webpage containing navigation and login elements.

   - Inside the header, there is a logo image of a company or brand (possibly Flipkart).
   - A paragraph that says "Explore plus," where "plus" is enclosed in a `span` with a class of "plus-class."
   - A search bar with a text input field and a search icon represented by a material icon.
   - A "Login" button for user authentication.
   - A set of navigation links represented as an unordered list (`ul`) containing:
     - "Become a Seller" link.
     - A "More" link with an expand_more icon.
     - A "Cart" link with a shopping_cart icon.

2. **Categories Section (`section class="items"`)**: This section contains links to various categories of products.

   - Each category is represented by a `div` with the class "items-links."
   - Within each category `div`, there is:
     - An anchor (`a`) wrapping an image that represents the category.
     - Another anchor wrapping a paragraph (`p`) containing the name of the category.
     - In some cases, there's an expand_more icon (material icon) indicating additional options related to the category.

The webpage seems to be a navigation menu for an online shopping website, with categories like Grocery, Mobiles, Fashion, Electronics, Home & Furniture, Appliances, Travel, Beauty & Toys, and Two-Wheelers. Each category has an image icon and a name, and some categories have additional options that can be expanded.

# CSS

![image](https://github.com/Ayush19bansal/flilipkart_navbar/assets/118842033/bc04c3e3-9c96-498e-8622-f2a184973e54)
![image](https://github.com/Ayush19bansal/flilipkart_navbar/assets/118842033/d56e8a21-f153-419a-b48d-a6ea5ecc303f)
![image](https://github.com/Ayush19bansal/flilipkart_navbar/assets/118842033/f5c24009-f5d0-46f5-827c-f46646ce8da5)

Certainly! The provided CSS code is used to style a webpage's elements, including the header and category links. Here's a short explanation of each part:

1. **Font Import and Global Styles**:
   - Google Fonts 'Poppins' and 'Roboto Serif' are imported for font usage.
   - `*`: Resets default margin, padding, and box-sizing behavior for all elements.
   - `font-family`: Sets the default font to 'Roboto Serif'.

2. **Navbar (`navbar-top`)**:
   - Background color is set to a blue shade (#3E71E7).
   - Uses flexbox to center content horizontally and vertically.
   - Padding and height are defined, allowing content wrapping if necessary.
   - The "plus" class changes the color to yellow and increases font weight.
   - Styles for the logo, search bar, and navigation links.

3. **Left Section (`left`)**:
   - Paragraph text color is set to white.
   - The paragraph is slightly moved up (relative positioning) and font size is reduced.

4. **Logo (`flip-img`)**:
   - Sets the dimensions of the logo image.

5. **Search Bar (`search`)**:
   - Styled search bar with white background, padding, and margins.
   - Rounded corners (border radius) and a shadow for a raised appearance.
   - The search input field has a defined width, border removed, and no outline.

6. **"Login" Button (`loginbut`)**:
   - Styled button with padding, white background, and blue text color.
   - Border is removed, font size is set, and outline is removed.

7. **Navigation Links (`links ul` and `links ul li`)**:
   - Navigation links are arranged in a row using flexbox.
   - Links have padding, color, and font size defined.

8. **Category Section (`items`)**:
   - Background color set to white.
   - Categories are centered in a row with defined width and height.
   - Categories have a gap and are wrapped if they exceed the container's width.
   - A subtle box shadow is applied.

9. **Category Links (`items-links img`, `items-links p`, `items-links .material-icons`, and `items-links a`)**:
   - Category images have a specific width and margin.
   - Category names have a defined font size, bold text, and centered alignment.
   - Material icons within category links are styled with specific font size and bold text.
   - Links have no text decoration and are colored black.

In summary, this CSS code provides styles for a webpage's header, navigation, and category links, creating a visually appealing and coherent design.
