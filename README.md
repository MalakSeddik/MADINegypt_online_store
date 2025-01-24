# MADIN Egypt - Clothing Marketplace

## Overview

**MADIN Egypt** is a modern, user-friendly online clothing marketplace designed to cater to both adults and kids, with separate categories for each gender. The platform is built to provide a seamless shopping experience, offering a wide range of clothing options for men, women, boys, and girls. The project leverages a robust tech stack including **React**, **Node.js**, **Express.js**, **MongoDB**, **JavaScript**, **HTML**, and **CSS** to deliver a responsive and dynamic web application.

## Features

- **User Authentication**: Secure user registration and login system.
- **Product Categories**: Organized into adults and kids sections, further divided by gender.
- **Product Listings**: Detailed product pages with images, descriptions, prices, and sizes.
- **Search and Filter**: Advanced search and filtering options to easily find products.
- **Shopping Cart**: Users can add products to their cart and proceed to checkout.
- **Responsive Design**: Fully responsive design ensuring a great experience on all devices.
- **Admin Panel**: An admin interface to manage products, categories, and orders.

## Technologies Used

- **Frontend**: 
  - **React**: A JavaScript library for building user interfaces.
  - **HTML/CSS**: For structuring and styling the web pages.
  - **JavaScript**: For adding interactivity and dynamic content.

- **Backend**:
  - **Node.js**: A JavaScript runtime for building scalable network applications.
  - **Express.js**: A web application framework for Node.js, simplifying server-side development.
  - **MongoDB**: A NoSQL database for storing product, user, and order data.

- **Other Tools**:
  - **Mongoose**: An ODM (Object Data Modeling) library for MongoDB and Node.js.
  - **Bootstrap**: A CSS framework for responsive design and pre-built components.

## Installation

To get a local copy up and running, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MalakSeddik/MADINegypt_online_store
.git
   cd MADINegypt_online_store
   ```

2. **Install dependencies**:
   ```bash
   npm install
   cd client
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env` file in the root directory and add the following variables:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   PORT=5000
   ```

4. **Run the application**:
   - Start the backend server:
     ```bash
     npm run server
     ```
   - Start the frontend development server:
     ```bash
     cd client
     npm start
     ```

5. **Access the application**:
   Open your browser and navigate to `http://localhost:3000`.

## Project Structure

```
MADINegypt_online_store
│   
├───admin
│   │   .gitignore
│   │   package-lock.json
│   │   package.json
│   │   README.md
│   │   
│   ├───public
│   │       favicon.ico
│   │       index.html
│   │       manifest.json
│   │       robots.txt
│   │       
│   └───src
│       │   App.js
│       │   index.css
│       │   index.js
│       │   
│       ├───Components
│       │   ├───AddProduct
│       │   │       AddProduct.css
│       │   │       AddProduct.jsx
│       │   │       
│       │   ├───Assets
│       │   │       arrow_icon.svg
│       │   │       cross_icon.png
│       │   │       nav-logo.svg
│       │   │       nav-profile.svg
│       │   │       Product_Cart.svg
│       │   │       Product_list_icon.svg
│       │   │       upload_area.svg
│       │   │       upload_cloud_icon.svg
│       │   │       
│       │   ├───Footer
│       │   │       Footer.css
│       │   │       Footer.jsx
│       │   │       
│       │   ├───ListProduct
│       │   │       ListProduct.css
│       │   │       ListProduct.jsx
│       │   │       
│       │   ├───Navbar
│       │   │       Navbar.css
│       │   │       Navbar.jsx
│       │   │       
│       │   └───Sidebar
│       │           Sidebar.css
│       │           Sidebar.jsx
│       │           
│       └───Pages
│           │   Admin.jsx
│           │   
│           └───CSS
│                   Admin.css
│                   
├───backend
│   │   .env
│   │   .gitignore
│   │   index.js
│   │   package-lock.json
│   │   package.json
│   │   
│   └───upload
│       └───images
└───frontend
    │   .gitignore
    │   package-lock.json
    │   package.json
    │   README.md
    │   
    ├───public
    │       favicon.ico
    │       index.html
    │       manifest.json
    │       robots.txt
    │       
    └───src
        │   App.js
        │   
        └───Components
            ├───Assets
            │       arrow.png
            │       banner_kids.png
            │       banner_mens.png
            │       banner_women.png
            │       breadcrum_arrow.png
            │       cart_cross_icon.png
            │       cart_icon.png
            │       cart_product_icon.png
            │       dropdown_icon.png
            │       exclusive_image.png
            │       hand_icon.png
            │       hero_image.png
            │       instagram_icon.png
            │       logo.png
            │       logo_big.png
            │       nav_dropdown.png
            │       p1_product.png
            │       p1_product_i1.png
            │       p1_product_i2.png
            │       p1_product_i3.png
            │       p1_product_i4.png
            │       pintester_icon.png
            │       product_1.png
            │       product_10.png
            │       product_11.png
            │       product_12.png
            │       product_13.png
            │       product_14.png
            │       product_15.png
            │       product_16.png
            │       product_17.png
            │       product_18.png
            │       product_19.png
            │       product_2.png
            │       product_20.png
            │       product_21.png
            │       product_22.png
            │       product_23.png
            │       product_24.png
            │       product_25.png
            │       product_26.png
            │       product_27.png
            │       product_28.png
            │       product_29.png
            │       product_3.png
            │       product_30.png
            │       product_31.png
            │       product_32.png
            │       product_33.png
            │       product_34.png
            │       product_35.png
            │       product_36.png
            │       product_4.png
            │       product_5.png
            │       product_6.png
            │       product_7.png
            │       product_8.png
            │       product_9.png
            │       star_dull_icon.png
            │       star_icon.png
            │       whatsapp_icon.png
            │       
            ├───Breadcrums
            │       Breadcrums.css
            │       Breadcrums.jsx
            │       
            ├───CartItems
            │       CartItems.css
            │       CartItems.jsx
            │       
            ├───DescriptionBox
            │       DescriptionBox.css
            │       DescriptionBox.jsx
            │       
            ├───Footer
            │       Footer.css
            │       Footer.jsx
            │       
            ├───Hero
            │       Hero.css
            │       Hero.jsx
            │       
            ├───Item
            │       Item.css
            │       Item.jsx
            │       
            ├───Navbar
            │       Navbar.css
            │       Navbar.jsx
            │       
            ├───NewCollections
            │       NewCollections.css
            │       NewCollections.jsx
            │       
            ├───NewsLetter
            │       NewsLetter.css
            │       NewsLetter.jsx
            │       
            ├───Offers
            │       Offers.css
            │       Offers.jsx
            │       
            ├───Popular
            │       Popular.css
            │       Popular.jsx
            │       
            └───ProductDisplay
                    ProductDisplay.css
                    ProductDisplay.jsx
                    

```

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Malak Seddik - [LinkedIn](https://www.linkedin.com/in/malakseddik) - M.Ragab0879@student.aast.edu

Project Link: [https://github.com/yourusername/madin-egypt](https://github.com/yourusername/madin-egypt)

## Acknowledgments

- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [Express.js Documentation](https://expressjs.com/)
- [MongoDB Documentation](https://docs.mongodb.com/)
- [Bootstrap Documentation](https://getbootstrap.com/docs/5.1/getting-started/introduction/)

---

Thank you for checking out MADIN Egypt! We hope you find this project useful and inspiring. Happy coding! 🚀
