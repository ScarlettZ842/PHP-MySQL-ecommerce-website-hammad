# A Complete PHP/MySQL based web application:

## Quick Start with Docker

### Prerequisites

- Docker installed on your system
- Docker Compose installed

### Running the Application

1. **Start the application:**

   ```bash
   docker compose up -d
   ```

2. **Wait for the database to initialize** (first run only, takes ~30 seconds)

3. **Access the application:**
   - Frontend: http://localhost:8080
   - Admin Panel: http://localhost:8080/admin/login.php

### Admin Credentials

**Primary Admin Account:**

- **Email:** hammad.shahir@gmail.com
- **Password:** 1234
- **Role:** Super Admin

**Secondary Admin Account:**

- **Email:** mc170200216@vu.edu.pk
- **Password:** 1234
- **Role:** Admin

> **Security Note:** Change these default passwords immediately after first login in a production environment.

### Useful Docker Commands

- **Stop the application:**

  ```bash
  docker compose down
  ```

- **Stop and remove volumes (complete reset):**

  ```bash
  docker compose down -v
  ```

- **View logs:**

  ```bash
  docker compose logs -f
  ```

- **Restart services:**
  ```bash
  docker compose restart
  ```

### Database Access

- **Host:** localhost (or `db` from within containers)
- **Port:** 3306
- **Database:** fashiony_ogs
- **Username:** fashiony_ogs
- **Password:** simple123
- **Root Password:** root_password

### Troubleshooting

1. **Port conflicts:** If port 8080 or 3306 is already in use, modify the ports in docker-compose.yml
2. **Database connection issues:** Wait for the MySQL healthcheck to pass (check with `docker compose ps`)
3. **Permission issues:** Ensure the uploads directory has write permissions

---

## Features

The complete ecommerce script with Paypal integration. Some of the features are as follow:

**Admin/Dashboard Area**

**Multi-level Category Management:**

-- Add Category
-- Edit Category
-- Delete Category
-- Manage Category Logo
-- Manage Category Slider
-- Add Sub-Category
-- Edit Sub-Category
-- Delete Sub-Category
-- Manage Sub-Category Slider

**Product Management:**

-- Multiple Product Image
-- Set Feature's Product
-- Product Description
-- Manage Product Reviews & Ratings
-- Product Stock Management
-- Offer / Discount Set
-- Unlimited Product Photo's
-- Related Product Selection
-- Add Product
-- Edit Product
-- Delete Product
-- Manage Product Category

**Oders Management:**

-- View All Order
-- Awaiting Payment
-- Awaiting Delivery

**Payment Setting:**

-- Unlimited Payment Method Creation.
-- Add / Edit / Delete Payment Method
-- Payment Method Icon Manage

**Frontend**

-- Fully Responsive Design.
-- Easy to Use Menu.
-- Delighted Product View Section.
-- Easy to product compare.
-- Online Order & payment System.
-- Product Rating system.
-- Product Review System.
-- SEO Friendly URL.
-- Easy to Social Share System.
-- User Registration & Login System.
-- User Database.
-- Easy to order system.
-- Social Links.

**Menu Setting**

-- Add / Edit / Delete Unlimited Menu.
-- Add / Edit / Delete Menu Content.
-- Set Menu Position

**CMS / Website Setting**

-- General Setting
-- Logo Setting
-- Footer Logo Setting
-- 4 Feature Setting
-- Home Slider Setting
-- 3 Top Images
-- Home Text Slider
-- Brand Logo Setting
-- Cat Slider Setting
-- Social Links
-- Payment Icon
-- Footer Menu

**User Panel**

-- Fully Responsive Design.
-- Easy to Registration.
-- Trace Product Delivery.
-- Online Order Management.
-- Portfolio Management.
-- Review Modify Facility.
-- Product Comment's Panel.
-- Report / Activity Section.
-- SEO Friendly URL.
-- Product Database.
-- Easy to order system.
