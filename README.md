# 🛍️ Stylify - Flutter E-commerce App

## 🛠 Tech Stack

**Mobile Development**:
- Flutter (Cross-platform Framework)
- Firebase (Backend & Authentication)
- BLoC Pattern (State Management)

**Architecture**:
- Clean Architecture
- Domain-Driven Design
- Repository Pattern

## 🌟 Key Features

- 🔐 User Authentication
- 🏪 Product Catalog
- 🛒 Shopping Cart Management
- 🔍 Product Search
- 📱 Responsive UI Design
- 🎨 Custom Font Integration
- 📦 Order Management
- 🗂️ Category Navigation

## 📂 Project Structure

```
stylify/
├── lib/
│   ├── common/        # Shared components & utilities
│   │   ├── bloc/      # Shared BLoC components
│   │   ├── helper/    # Helper functions
│   │   └── widgets/   # Reusable widgets
│   ├── core/          # Core application logic
│   │   ├── configs/   # App configurations
│   │   ├── constants/ # Constants and enums
│   │   └── usecase/   # Business logic use cases
│   ├── data/          # Data layer
│   │   ├── auth/      # Authentication data
│   │   ├── category/  # Category data
│   │   ├── order/     # Order data
│   │   └── product/   # Product data
│   ├── domain/        # Domain layer
│   │   ├── auth/      # Auth entities & repos
│   │   ├── category/  # Category entities & repos
│   │   ├── order/     # Order entities & repos
│   │   └── product/   # Product entities & repos
│   └── presentation/  # UI layer
│       ├── auth/      # Auth screens
│       ├── cart/      # Cart screens
│       ├── home/      # Home screens
│       └── product/   # Product screens
└── assets/           # App resources
    ├── fonts/        # Custom fonts
    ├── images/       # Image assets
    └── vectors/      # SVG assets
```

## 🖥 Local Setup

1. **Prerequisites**
   - Flutter SDK
   - Android Studio / VS Code
   - Firebase project setup

2. **Installation**
   ```bash
   # Clone the repository
   git clone [repository-url]

   # Install dependencies
   flutter pub get

   # Run the app
   flutter run
   ```

3. **Firebase Setup**
   - Create a Firebase project
   - Add Android & iOS apps
   - Download and add configuration files
   - Enable Authentication and Cloud Firestore

## 👨‍💻 Author
- GitHub: [@hashiifabdillah](https://github.com/hashiifab)
- LinkedIn: [Hashiif Abdillah](https://www.linkedin.com/in/hashiif-abdillah-665373297/)
