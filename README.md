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

- Add Category
- Edit Category
- Delete Category
- Manage Category Logo
- Manage Category Slider
- Add Sub-Category
- Edit Sub-Category
- Delete Sub-Category
- Manage Sub-Category Slider

**Product Management:**

- Multiple Product Image
- Set Feature's Product
- Product Description
- Manage Product Reviews & Ratings
- Product Stock Management
- Offer / Discount Set
- Unlimited Product Photo's
- Related Product Selection
- Add Product
- Edit Product
- Delete Product
- Manage Product Category

**Oders Management:**

- View All Order
- Awaiting Payment
- Awaiting Delivery

**Payment Setting:**

- Unlimited Payment Method Creation.
- Add / Edit / Delete Payment Method
- Payment Method Icon Manage

**Frontend**

- Fully Responsive Design.
- Easy to Use Menu.
- Delighted Product View Section.
- Easy to product compare.
- Online Order & payment System.
- Product Rating system.
- Product Review System.
- SEO Friendly URL.
- Easy to Social Share System.
- User Registration & Login System.
- User Database.
- Easy to order system.
- Social Links.

**Menu Setting**

- Add / Edit / Delete Unlimited Menu.
- Add / Edit / Delete Menu Content.
- Set Menu Position

**CMS / Website Setting**

- General Setting
- Logo Setting
- Footer Logo Setting
- 4 Feature Setting
- Home Slider Setting
- 3 Top Images
- Home Text Slider
- Brand Logo Setting
- Cat Slider Setting
- Social Links
- Payment Icon
- Footer Menu

**User Panel**

- Fully Responsive Design.
- Easy to Registration.
- Trace Product Delivery.
- Online Order Management.
- Portfolio Management.
- Review Modify Facility.
- Product Comment's Panel.
- Report / Activity Section.
- SEO Friendly URL.
- Product Database.
- Easy to order system.

### Web App User
<img width="1387" height="739" alt="Screenshot 2026-01-06 at 14 37 24" src="https://github.com/user-attachments/assets/5729eb0c-18fe-4ba8-b97c-5ff8912febda" />
<img width="1421" height="747" alt="Screenshot 2026-01-06 at 14 37 39" src="https://github.com/user-attachments/assets/b9cf5345-0a82-4377-885a-ca2a0958b26f" />
<img width="1422" height="742" alt="Screenshot 2026-01-06 at 14 38 26" src="https://github.com/user-attachments/assets/581fdfc3-3e58-4646-98e8-dfb88c723236" />
<img width="1416" height="730" alt="Screenshot 2026-01-06 at 14 39 53" src="https://github.com/user-attachments/assets/70cf6d1a-ed33-4d79-94de-34edb674db69" />
<img width="1418" height="739" alt="Screenshot 2026-01-06 at 14 40 28" src="https://github.com/user-attachments/assets/335fd26c-8c1f-4a7d-8732-4c2f56c5882a" />
<img width="1416" height="734" alt="Screenshot 2026-01-06 at 14 40 40" src="https://github.com/user-attachments/assets/ebc6dbae-0b23-4699-a650-6fe01fb6b733" />
<img width="1395" height="740" alt="Screenshot 2026-01-06 at 14 41 07" src="https://github.com/user-attachments/assets/bf15bbaf-02c2-4d7c-82b6-f64baa3b30f6" />
<img width="1415" height="738" alt="Screenshot 2026-01-06 at 14 44 04" src="https://github.com/user-attachments/assets/a6f6c754-107f-4c21-86e7-af86edfaa6d2" />
<img width="1419" height="744" alt="Screenshot 2026-01-06 at 14 44 12" src="https://github.com/user-attachments/assets/cc528fec-8edf-40d0-9fa7-d67731efacc1" />

### Web App Admin
<img width="1421" height="690" alt="Screenshot 2026-01-06 at 14 41 32" src="https://github.com/user-attachments/assets/85216a8a-1299-46cf-9814-beb9ed0b9911" />
<img width="1400" height="742" alt="Screenshot 2026-01-06 at 14 41 42" src="https://github.com/user-attachments/assets/0ab94bd9-fd2a-4084-8cd7-5bb23ac1174f" />









