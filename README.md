# FigMo

FigMo is a modern, general-purpose e-commerce website designed to provide a seamless shopping experience for users. It allows customers to browse, search, and purchase a wide variety of products across multiple categories. FigMo emphasizes simplicity, speed, and user-friendly design, making online shopping easy and enjoyable.

---
## Features
- Product browsing and category navigation
- Search and filter functionality 
- Shopping cart and checkout process
- User account management

FigMo is designed to be scalable, flexible, and brandable, making it suitable as a general marketplace like the big brand companies.

---
## Usage

### Browsing and Searching
1. Open the frontend `index.html` in your browser.
2. Browse products by category or use the search bar to find specific items.
3. Click on a product to view its details on `product.html`.

### Shopping Cart
1. On a product page, click **Add to Cart** to add items.
2. Navigate to `pages/cart.html` to view your cart.
3. Adjust quantities or remove items as needed.
4. Click **Proceed to Checkout** to go to `checkout.html`.

### Checkout
1. Enter your shipping and payment information.
2. Review your order summary.
3. Click **Place Order** to complete the purchase.
4. Orders are saved in the backend database.

### User Accounts
- Users can **register and login** (if implemented).
- Account details and order history can be viewed and managed in the backend.
---
## File Structure 
```
FigMo/
├── backend/
│   ├── src/main/java/com/figmo/
│   │   ├── controller/
│   │   ├── model/
│   │   ├── repository/
│   │   └── service/
│   ├── src/main/resources/
│   │   └── application.properties
│   └── pom.xml
│
├── database/
│   ├── schema.sql
│   └── seed.sql
│
├── frontend/
│   ├── assets/
│   │   ├── css/
│   │   │   └── style.css
│   │   └── js/
│   │       └── main.js
│   ├── images/
│   │   ├── image1
│   │   └── image2
│   ├── pages/
│   │   ├── cart.html
│   │   ├── checkout.html
│   │   └── product.html
│   └── index.html
└── README.md 
```
## Getting Started
### Prerequisites 

- **Java 17+**
- **Maven**
- **MySql**
---
### Backend
```bash
cd backend
mvn clean install
mvn spring-boot:run
```
### Database

```bash
# from SQL client or terminal
source  ../database/schema.sql;
source  ../database/seed/sql;
```
### Frontend
```bash
cd frontend
# open index.html in browser
open index.html
```
---
![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)

Copyright (c) 2025 Jos

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.