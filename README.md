# Restyle Mobile - House Remodeling Monitoring App 🏠📱

A mobile application for monitoring and managing house remodeling projects, connecting contractors and businesses in the construction industry.

## 📋 Overview

Restyle Mobile is an Android application designed to streamline the house remodeling process by providing a platform where:
- **Contractors** can find and connect with remodeling businesses
- **Businesses** can showcase their portfolio and manage projects
- **Users** can track the progress of their remodeling projects

## 🚀 Features

### 🔐 Authentication
- User registration and login system
- Password recovery functionality
- Google Sign-In integration
- Secure token-based authentication

### 🏢 Business Management
- Business profile creation and management
- Portfolio showcase with project galleries
- Search and filter businesses by expertise and location
- Business ratings and reviews

### 📊 Project Management
- Project creation and tracking
- Progress monitoring with visual updates
- Image upload and documentation
- Timeline management with start and finish dates

### 👤 User Profiles
- Personal and company profile management
- Edit profile information
- Image upload capabilities

## 🛠 Tech Stack

### **Frontend**
- **Kotlin** - Primary programming language
- **Android SDK** (API 24-34) - Native Android development
- **Material Design Components** - UI/UX framework
- **ConstraintLayout** - Flexible layout system

### **Networking & APIs**
- **Retrofit 2.11.0** - HTTP client for API communication
- **OkHttp 4.10.0** - Network layer and interceptors
- **Gson Converter** - JSON serialization/deserialization

### **Image Processing**
- **Glide 4.15.1** - Image loading and caching
- **Picasso 2.8** - Image manipulation
- **Imgur API** - Cloud image hosting integration

### **Google Services**
- **Google Play Services Auth** - Google Sign-In authentication

### **Testing**
- **JUnit** - Unit testing framework
- **Espresso** - UI testing framework
- **AndroidX Test** - Android testing libraries

### **Build Tools**
- **Gradle 8.7** - Build automation
- **Kotlin DSL** - Build scripts
- **ProGuard** - Code obfuscation and optimization

## 📱 Application Architecture

### Package Structure
```
com.example.restyle_mobile/
├── Beans/                    # Data models (Business, Project, User)
├── Interface/                # API services and Retrofit client
├── Fragment/                 # UI fragments (Login, Dialog, etc.)
├── Persistence/              # Local data storage
├── business_portfolio/       # Business portfolio features
│   ├── Activity/            # Portfolio and project creation activities
│   ├── Adapter/             # RecyclerView adapters
│   ├── Fragment/            # Portfolio fragments
│   └── Repository/          # Data repository layer
├── business_search/          # Business search functionality
│   ├── Activity/            # Search activities
│   ├── Adapter/             # Search result adapters
│   └── Fragment/            # Search fragments
└── home_screen/              # Main application entry point
    └── Activity/            # Home screen activities
```

### Key Components
- **Activities**: Main application screens
- **Fragments**: Reusable UI components
- **Adapters**: RecyclerView data binding
- **Services**: API communication interfaces
- **Beans**: Data model classes
- **Repositories**: Data access layer

## 🔧 Setup & Installation

### Prerequisites
- Android Studio Arctic Fox or later
- Android SDK API Level 24 or higher
- Kotlin 1.8+
- Java 8+

### Installation Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/PaoloParragaGamarra/Mobilie-Monitoring-House-Remodeling.git
   cd restyle-mobile
   ```

2. **Open in Android Studio**
   - Launch Android Studio
   - Select "Open an existing project"
   - Navigate to the project directory

3. **Sync Project**
   - Let Gradle sync all dependencies
   - Ensure all required SDKs are installed

4. **Configure API Keys**
   - Add your Imgur API client ID to the project
   - Configure any required backend API endpoints

5. **Run the Application**
   - Connect an Android device or start an emulator
   - Click "Run" in Android Studio

## 📡 API Integration

The application integrates with several APIs:
- **Custom Backend API** - User authentication and business data
- **Imgur API** - Image upload and hosting
- **Google APIs** - Authentication services

## 🎨 UI/UX Features

- **Material Design 3** components
- **Dark/Light theme** support
- **Responsive layouts** for different screen sizes
- **Smooth animations** and transitions
- **Custom fonts** and styling
- **Bottom navigation** for easy access

## 📁 Key Files

| File | Purpose |
|------|---------||
| `build.gradle.kts` | Project configuration and dependencies |
| `AndroidManifest.xml` | App permissions and component declarations |
| `strings.xml` | Localized text resources |
| `RetrofitClient.kt` | API client configuration |
| `HomeActivity.kt` | Main application entry point |

## 🔒 Permissions

The application requires the following permissions:
- **INTERNET** - Network communication
- **READ_EXTERNAL_STORAGE** - Access device photos
- **WRITE_EXTERNAL_STORAGE** - Save images locally

## 🚧 Development Status

This project is actively under development. Current focus areas:
- Enhanced user authentication
- Improved project tracking features
- Real-time notifications
- Advanced search and filtering
- Performance optimizations

## 👥 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Contact

**Paolo Parraga Gamarra**
- GitHub: [@PaoloParragaGamarra](https://github.com/PaoloParragaGamarra)
- Project Link: [https://github.com/PaoloParragaGamarra/Mobilie-Monitoring-House-Remodeling](https://github.com/PaoloParragaGamarra/Mobilie-Monitoring-House-Remodeling)

---

*Built with ❤️ using Kotlin and Android Studio*
