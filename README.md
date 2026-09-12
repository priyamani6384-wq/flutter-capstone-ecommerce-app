# Mobile App Capstone - E-Commerce Complete App
Final Project - Flutter Fast Track - Codomax Digital Solutions

## System Models & Architecture
- MVVM Architecture
- Models: User, Product, Cart with JSON serialization
- Navigation: Bottom Navigation, Auth Flow, Cart Flow
- State Management: setState simulating Riverpod/Bloc pattern

## UI Wireframes
- Auth Screen -> Home Grid -> Product Detail -> Cart -> Checkout -> Profile
- Figma Design: E-commerce layout with search, grid, cart, checkout
- Responsive UI with Material Design

## Backend Setup
- REST API: Product fetching with JSON parsing (http package)
- Firebase: Authentication (Email/Password), Firestore (products, users, orders collections)
- Local DB: Cart persistence using SharedPreferences/Hive (simulated)
- Security Rules: allow read/write if auth != null && request.auth.uid == owner

## Hardware Integrations
- Location: Geolocator package - Delivery address tracking (Vellore, TN)
- Camera Overlay & Gallery: Image Picker for product reviews
- Notifications: Firebase Cloud Messaging for order updates
- Device Permissions: Camera, Location, Storage handling

## Test Build & Performance
- APK: flutter build apk --release - Ready for testing
- Performance Profiling: Error catching, build configs, profiling enabled
- Video Demo: Full app flow screen recording
- Build Version: v1.0.0 Release

## Features Implemented
✅ Firebase Authentication
✅ Product Search & Filter (REST API)
✅ Add to Cart with Local DB persistence
✅ Location Integration
✅ Camera & Gallery Integration
✅ Push Notifications
✅ Checkout & Order Placement

Built by Priyadharshini Subramaniyan - Rank #14
Codomax Digital Solutions - Flutter Fast Track Internship
