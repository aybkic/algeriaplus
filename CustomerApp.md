# Customer Mobile Application Documentation

## Overview
The Customer App is a Flutter-based mobile application that serves as the customer-facing platform for the Algeria Plus delivery system.

## Project Structure

### Root Directory
- `android/` - Android platform-specific code and configurations
- `ios/` - iOS platform-specific code and configurations
- `lib/` - Main Flutter application source code
- `assets/` - Static assets (images, fonts, etc.)
- `test/` - Application test files

### Configuration Files
- `pubspec.yaml` - Flutter project configuration and dependencies
- `pubspec.lock` - Locked versions of dependencies
- `flutter_application_id.yaml` - Application ID configuration
- `flutter_native_splash.yaml` - Splash screen configuration
- `analysis_options.yaml` - Dart analyzer configuration

### Platform-Specific Directories

#### Android (`android/`)
- Native Android configuration
- Gradle build files
- Android manifest
- Platform-specific plugins
- Firebase configuration

#### iOS (`ios/`)
- Xcode project files
- CocoaPods configuration
- Info.plist
- Platform-specific plugins
- Firebase configuration

### Main Application Code (`lib/`)
Contains 543 files organized in various directories:

#### Common Structure:
- `screens/` - UI screens and pages
- `widgets/` - Reusable UI components
- `models/` - Data models
- `services/` - API and business logic services
- `utils/` - Utility functions and helpers
- `providers/` - State management
- `constants/` - Application constants
- `theme/` - UI theme configuration
- `localization/` - Multi-language support

### Assets (`assets/`)
17 files including:
- Images
- Icons
- Fonts
- JSON files
- Configuration files

## Key Features

### Authentication
- Phone number authentication
- Social media login
- Profile management

### Shopping
- Product browsing and search
- Category navigation
- Cart management
- Wishlist functionality

### Orders
- Order placement
- Real-time order tracking
- Order history
- Delivery status updates

### Payment
- Multiple payment methods
- Secure payment processing
- Transaction history
- Wallet management

### Additional Features
- Push notifications
- Address management
- Rating and reviews
- Chat support
- Language selection
- Theme customization

## Technical Details

### State Management
- Provider/Bloc pattern for state management
- Reactive programming principles

### API Integration
- RESTful API communication
- Real-time updates using WebSockets
- Secure API authentication

### Storage
- Local storage for offline capability
- Secure credential storage
- Cache management

### Performance
- Lazy loading
- Image optimization
- Efficient state management
- Memory optimization

## Development Guidelines

### Code Organization
- Feature-based structure
- Separation of concerns
- Clean architecture principles
- SOLID principles

### Testing
- Unit tests
- Widget tests
- Integration tests

### Build & Deploy
- Development build configuration
- Production build optimization
- CI/CD setup
- App signing configuration
