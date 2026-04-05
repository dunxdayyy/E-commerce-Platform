---
title: Product Requirement Document
doc_id: PRD-001
version: 0.1.0
status: draft
owner: @PM
reviewers: [@SA, @BE]
created: 2026-04-05
updated: 2026-04-05
---

# Product Requirement Document (PRD)

## 1. Overview

DG is a multi-vendor e-commerce platform that allows sellers to create shops and customers to purchase products.

---

## 2. User Roles

### 2.1 Customer

- Browse products
- Add to cart
- Checkout
- Make payment

### 2.2 Seller

- Create and manage shop
- Add/edit products
- Manage orders

### 2.3 Admin

- Manage users
- Monitor orders
- System configuration

---

## 3. Core Features

### 3.1 Authentication

- Register
- Login
- JWT-based authentication

---

### 3.2 Product Management

- Create product
- Update product
- Delete product
- Product variants

---

### 3.3 Cart

- Add to cart
- Update quantity
- Remove item

---

### 3.4 Order

- Create order
- Order status tracking

---

### 3.5 Payment

- Payment integration (mock initially)

---

### 3.6 Multi-vendor

- Each order can contain products from multiple sellers
- System splits order per seller

---

## 4. User Flow

### 4.1 Purchase Flow

Customer → Browse → Add to cart → Checkout → Payment → Order created

---

## 5. Non-functional Requirements

- Scalable architecture
- Secure authentication
- High availability
