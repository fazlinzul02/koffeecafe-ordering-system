# Koffee Cafe — Ordering System

A web-based cafe ordering and menu management system built with **PHP** and **MySQL**, designed to run on a local web server stack such as **XAMPP** with **Apache** and **MySQL**.

---

## Features

- **Customer Browsing & Ordering:** View the home page (`index.php`) and about section (`about.php`), manage cart actions (`cart_process.php`), and complete orders (`checkout.php`).
- **Authentication & Sessions:** User sign-in (`login.php`), authentication handling (`auth.php`), and session sign-out (`logout.php`).
- **Menu & Product Management:** Add (`add_menu.php`, `add_product.php`), update (`edit_product.php`), manage (`manage_menu.php`), and remove (`delete_product.php`) menu items and products.
- **Admin & Order Handling:** Monitor activity via `admin_dashboard.php`, retrieve order items (`fetch_order_items.php`), and remove orders (`delete_order.php`)[cite: 2].

---

## Tech Stack

- **Backend:** PHP
- **Database:** MySQL (connected via `db_connect.php`)[cite: 2]
- **Frontend & Assets:** HTML/CSS/JavaScript (`css/`, `js/`, `sass/`, `fonts/`, `img/`, `Source/`)[cite: 2]
- **Local Server Environment:** XAMPP (Apache + MySQL + phpMyAdmin)

---

## Project Structure

```text
koffeecafe/
├── about.php               # About page
├── add_menu.php            # Add menu entries
├── add_product.php         # Add new products
├── admin_dashboard.php     # Admin overview dashboard
├── auth.php                # Authentication logic
├── cart_process.php        # Cart operations
├── checkout.php            # Order checkout flow
├── db_connect.php          # MySQL database connection
├── delete_order.php        # Delete order handler
├── delete_product.php      # Delete product handler
├── edit_product.php        # Edit existing product details
├── fetch_order_items.php   # Fetch order item records
├── index.php               # Main entry / landing page
├── login.php               # User/admin login page
├── logout.php              # Session logout handler
├── manage_menu.php         # Menu management interface
├── css/                    # Stylesheets
├── fonts/                  # Custom fonts
├── img/                    # Images and visual assets
├── js/                     # Client-side scripts
├── sass/                   # Sass source styles
└── Source/                 # Additional project source assets
