# E-Commerce Shop Platform - TODO

## Database & Schema
- [x] Design and create database schema (users, products, categories, cart, orders, etc.)
- [x] Create product images table for S3 storage
- [x] Create order items and order status tracking tables
- [x] Run database migrations

## Backend API Development
- [x] Create product management procedures (list, get, create, update, delete)
- [x] Create category management procedures
- [x] Create user/member management procedures
- [x] Create shopping cart procedures (add, remove, update quantity)
- [x] Create order procedures (create, list, get details, update status)
- [ ] Create order notification system
- [x] Implement role-based access control (admin/user)
- [x] Create product image upload/management procedures

## Stripe Integration
- [x] Add Stripe feature to project
- [x] Create Stripe payment intent procedures
- [x] Implement payment webhook handlers
- [ ] Create order confirmation after successful payment
- [ ] Implement payment status tracking

## Admin Dashboard
- [x] Create admin layout and navigation
- [x] Build product management page (list, add, edit, delete with images)
- [x] Build category management page
- [x] Build member/user management page (list, add, edit, delete, role assignment)
- [x] Build order management page (view orders, update status)
- [x] Build dashboard with statistics and analytics
- [x] Implement admin-only access control

## Frontend - Customer Pages
- [x] Create elegant landing/home page
- [x] Build product listing page with pagination
- [x] Implement product search functionality
- [x] Implement product filtering by category and price
- [x] Create product detail page
- [x] Build shopping cart page
- [x] Create checkout page with Stripe integration
- [x] Build order history/tracking page for users
- [x] Create user profile/account management page

## Shopping Cart & Checkout
- [x] Implement cart state management
- [x] Create cart persistence (localStorage/database)
- [x] Build checkout flow with address collection
- [x] Integrate Stripe payment form
- [ ] Implement order confirmation page

## Notifications System
- [x] Create notifications table in database
- [x] Implement notification router and procedures
- [ ] Send email notifications to admin on new order
- [ ] Create notification UI component
- [ ] Add notification bell icon to header

## Testing & Refinement
- [ ] Write vitest tests for backend procedures
- [ ] Test authentication and authorization
- [ ] Test product management workflows
- [ ] Test order creation and payment flow
- [ ] Test cart functionality
- [ ] UI/UX testing and refinement
- [ ] Performance optimization

## Phase 7 - Additional Enhancements
- [ ] Create About page
- [ ] Create Contact page
- [ ] Implement product reviews and ratings
- [ ] Add wishlist functionality
- [ ] Implement coupon/promo code system
- [ ] Add newsletter subscription
- [ ] Implement search suggestions/autocomplete
- [ ] Add product comparison feature

## Deployment & GitHub
- [ ] Create GitHub repository
- [ ] Push code to GitHub
- [ ] Set up GitHub Actions for CI/CD (optional)
- [ ] Deploy to production
- [ ] Set up custom domain (optional)

## Design & Styling
- [x] Define color palette and typography for elegant style (dark theme with gold accent)
- [x] Create consistent component library
- [x] Ensure responsive design across devices
- [x] Implement dark/light theme support (dark theme enabled)


## Phase 8 - Bug Fixes & Improvements
- [x] ปรับปรุงระบบสมาชิก OAuth ให้ทำงานได้ถูกต้อง
- [x] สร้าง Admin Panel ที่แยกจาก User interface
- [x] เพิ่มระบบ role-based access control ที่ชัดเจน
- [x] ปรับปรุงระบบแจ้งเตือน Admin เมื่อมีคำสั่งซื้อใหม่
- [x] เปลี่ยนข้อความทั้งหมดเป็นภาษาไทย
- [ ] ทดสอบระบบสมาชิกและการเข้าสู่ระบบ
- [ ] ทดสอบ Admin Panel และการจัดการข้อมูล
