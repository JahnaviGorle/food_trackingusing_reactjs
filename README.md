# Food Ordering Web App

## Overview
This is a **React-based food ordering application** that allows users to browse food items, add them to a cart, and complete purchases. It includes authentication, a secure checkout process, and real-time loading indicators.

## Features
- 🔐 **Authentication System** (Login & Register)
- 🍔 **Food Browsing & Searching**
- 🛒 **Cart Management**
- ✅ **Protected Checkout Process**
- 🚀 **Loading & Notification System**
- 🌍 **API Integration with Axios**

## Tech Stack
- **Frontend:** React, React Router, Context API
- **Backend:** Express.js (assumed), MongoDB (assumed)
- **Styling:** CSS, Google Fonts (Quicksand)
- **State Management:** Context API
- **Notifications:** React Toastify
- **Performance Monitoring:** Web Vitals

## Project Structure
```
📦 food-ordering-app
 ┣ 📂 src
 ┃ ┣ 📂 components
 ┃ ┃ ┣ 📂 Header
 ┃ ┃ ┣ 📂 Loading
 ┃ ┃ ┗ 📂 AuthRoute
 ┃ ┣ 📂 pages
 ┃ ┃ ┣ 📂 Home
 ┃ ┃ ┣ 📂 Food
 ┃ ┃ ┣ 📂 Cart
 ┃ ┃ ┣ 📂 Login
 ┃ ┃ ┣ 📂 Register
 ┃ ┃ ┗ 📂 Checkout
 ┃ ┣ 📂 hooks
 ┃ ┣ 📂 interceptors
 ┃ ┣ 📜 App.js
 ┃ ┣ 📜 AppRoutes.js
 ┃ ┣ 📜 axiosConfig.js
 ┃ ┣ 📜 index.js
 ┃ ┣ 📜 index.css
 ┃ ┗ 📜 reportWebVitals.js
```

## Installation
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/food-ordering-app.git
cd food-ordering-app
```
### 2️⃣ Install Dependencies
```sh
npm install
```
### 3️⃣ Start the Development Server
```sh
npm start
```

## Environment Variables
Create a `.env` file and configure the following:
```
REACT_APP_API_BASE_URL=http://localhost:5000
```

## Usage
- **Visit `http://localhost:3000`** to explore the app.
- **Register/Login** to access the cart and checkout.
- **Search for food items** and add them to your cart.
- **Proceed to checkout** (protected route, requires login).

## Lessons

### 1. Demo And Installation
- [x] Install [NodeJs](https://nodejs.org/en)
- [x] Install [Visual Studio Code](https://code.visualstudio.com)
- [x] Install [Git](https://git-scm.com)

### 2. Creating React App
- [x] Create React App
- [x] Remove Unnecessary Codes

### 3. Adding Header
- [x] Add Header.js
- [x] Use Header in App.js
- [x] Install react-router-dom in frontend
- [x] Add header.module.css
- [x] Use BrowserRouter inside index.js
- [x] Update Header.js
- [x] Update header.module.css

### 4. Adding Thumbnails
- [x] Add HomePage component
- [x] Add AppRoutes component
- [x] Use AppRoutes in App.js
- [x] Add data.js
- [x] Add food Images
- [x] Add foodService.js
- [x] Update HomePage.js
  - [x] Add Reducer
  - [x] Load foods
  - [x] Add Thumbnails.js
    - [x] Add CSS File
    - [x] Add Image
    - [x] Add Title
    - [x] Add Favorite Icon
    - [x] Add StarRating.js
      - [x] Add Star Images
      - [x] Add CSS
    - [x] Add Origins
    - [x] Add Cook Time
    - [x] Add Price.js
    - [x] Update CSS File

### 5. Adding Search
- [x] Add Search Route to AppRoutes.js
- [x] Add Search function to foodService.js
- [x] Use Search Inside HomePage.js
- [x] Add Search Component
  - [x] Add CSS

### 6. Adding Tags Bar
#### Showing The Tags:
- [x] Add sample_tags to data.js
- [x] Add getAllTags function to foodService.js
- [x] Add Tags Component
  - [x] Add Css
- [x] Use Tags Component in HomePage.js

#### Showing Foods By Tag
- [x] Add Tag route to AppRoutes.js
- [x] Add getAllByTag function to foodService.js
- [x] Use tag param in HomePage.js

### 7. Food Page
- [x] Create FoodPage Component
- [x] Add route to AppRoutes.js
- [x] Add getById function to foodService.js
- [x] Update FoodPage Component
  - [x] Load food
  - [x] Create Template
  - [x] Add Css

### 8. Cart Page
- [x] Create Cart Page Component
  - [x] Create css
- [x] Add cart route to the Routes
- [x] Create useCart Hook
  - [x] Add CartProvider to index.js
  - [x] Initialize cart with sample foods
- [x] Update Cart Page Component
  - [x] useCart hook
  - [x] Add Title Component
  - [x] Add JSX
  - [x] Add CSS
- [x] Update useCart Hook
  - [x] Add to cart
  - [x] Remove from cart
  - [x] Change quantity
  - [x] Saving To LocalStorage
- [x] In Food Page useCart for Add to cart buttons
- [x] In Header useCart for cart total count

## Contributing
Feel free to submit issues or pull requests for improvements.

## License
This project is licensed under the **MIT License**.

---
🚀 **Developed by Jahnavi Gorle**
