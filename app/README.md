# Omi App

The Omi App is a Flutter-based mobile application that serves as the companion app for Omi devices. This app enables users to interact with their Omi device, manage apps, and customize their experience.

## 📚 **[View Full App setup instructions in the documentation](https://docs.omi.me/docs/developer/AppSetup)**

## What's in the Documentation?

### 🛠 Development Setup
- **Firebase Setup**: Complete guide for configuring Firebase authentication and services
- **Environment Setup**: Step-by-step guide for .env configuration and API keys
- **Build Configuration**: Instructions for build runner and platform-specific setups
- **Manual Setup Option**: Alternative to automated setup for custom configurations
- **Troubleshooting Guide**: Common setup issues and their solutions

### 🚀 Advanced Topics
- **Backend Integration**: Guide for connecting to custom backend services
- **Production Setup**: Detailed Firebase configuration for production environment
- **Authentication**: Complete OAuth setup including SHA key generation
- **Multi-Environment**: Managing development and production configurations
- **Platform Specifics**: iOS and Android platform-specific requirements

### Quick Setup

1. Navigate to the app directory:
   ```bash
   cd app
   ```

2. Run setup script:
   ```bash
   # For iOS
   bash setup.sh ios

   # For Android
   bash setup.sh android

   # For macOS
   bash setup.sh macos
   ```

3. Run the app:
   ```bash
   # For iOS/Android
   flutter run --flavor dev

   # For macOS
   flutter run -d macos
   ```

## Need Help?

- 💬 Join our [Discord Community](http://discord.omi.me)
