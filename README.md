# 🚦 TrafficAZ - Intelligent Traffic Management System

<div align="center">

![TrafficAZ Logo](https://i.pinimg.com/originals/08/a4/67/08a467875def4f8c3cda15bb693263ee.gif)

**Revolutionizing Traffic Management in Cameroon with AI-Powered Real-Time Analytics**

[![React Native](https://img.shields.io/badge/React%20Native-0.79.5-blue.svg)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Expo-53.0.17-black.svg)](https://expo.dev/)
[![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android%20%7C%20Web-lightgrey.svg)](https://expo.dev/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

</div>

---

## FRONTEND IMPLEMENTATION

## 📋 Table of Contents

- [🚀 Overview](#-overview)
- [✨ Key Features](#-key-features)
- [🏗️ Architecture](#️-architecture)
- [🛠️ Technology Stack](#️-technology-stack)
- [📱 Screenshots](#-screenshots)
- [🚀 Getting Started](#-getting-started)
- [⚙️ Configuration](#️-configuration)
- [📖 API Documentation](#-api-documentation)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 🚀 Overview

**TrafficAZ** is a cutting-edge mobile application designed to revolutionize traffic management in Cameroon. Built with React Native and Expo, this intelligent system provides real-time traffic analytics, weather integration, voice commands, and community-driven traffic reporting.

### 🎯 Mission
To create a smarter, safer, and more efficient transportation ecosystem in Cameroon by leveraging real-time data, AI analytics, and community participation.

### 🌟 Vision
To become the leading traffic intelligence platform in Central Africa, empowering citizens and authorities with data-driven insights for better urban mobility.

---

## ✨ Key Features

### 🗺️ **Real-Time Traffic Analytics**
- **Live Traffic Monitoring**: Real-time tracking of vehicle speeds and congestion patterns
- **AI-Powered Analysis**: Machine learning algorithms for traffic pattern recognition
- **Heat Map Visualization**: Interactive maps showing traffic density and flow
- **Route Optimization**: Smart routing with traffic-aware pathfinding

### 🎤 **Voice-Activated Commands**
- **Hands-Free Operation**: "Hey TrafficAZ" wake word activation
- **Natural Language Processing**: Conversational traffic queries and reports
- **Multi-Language Support**: English and French voice recognition
- **Voice Feedback**: Audio responses for accessibility

### 🌤️ **Weather Integration**
- **Real-Time Weather Data**: OpenWeather API integration
- **Traffic-Weather Correlation**: Analysis of weather impact on traffic
- **Forecast Integration**: 5-day weather predictions affecting route planning
- **Smart Recommendations**: Weather-based driving suggestions

### 📍 **Location Services**
- **GPS Tracking**: High-accuracy location monitoring
- **Speed Detection**: Real-time speed calculation and analysis
- **Geofencing**: Location-based alerts and notifications
- **Route Planning**: Start-to-end navigation with traffic consideration

### 🚨 **Community Reporting**
- **Crowdsourced Alerts**: User-generated traffic reports
- **Real-Time Notifications**: Instant alerts to nearby users
- **Verification System**: Community validation of reports
- **Emergency Reporting**: Quick accident and incident reporting

### 📊 **Advanced Analytics**
- **Traffic Clustering**: AI-powered traffic pattern identification
- **Predictive Analytics**: Traffic forecasting based on historical data
- **Performance Metrics**: Detailed traffic statistics and insights
- **Export Capabilities**: Data export for analysis and reporting

---

## 🏗️ Architecture

```
TrafficAZ/
├── 📱 Frontend (React Native + Expo)
│   ├── 🎨 Components/          # Reusable UI components
│   ├── 📄 App/                 # Screen components and navigation
│   ├── 🔧 Services/            # API and business logic services
│   ├── 🌐 Context/             # React Context for state management
│   ├── 🎯 Constants/           # App configuration and constants
│   └── 🛠️ Utils/              # Helper functions and utilities
├── 🔗 Backend Integration
│   ├── 📡 REST API             # Traffic data endpoints
│   ├── 🧠 AI Analytics         # Machine learning models
│   └── 📊 Database             # Traffic and user data storage
└── 🌐 External APIs
    ├── 🌤️ OpenWeather         # Weather data
    ├── 🗺️ Google Maps         # Mapping and geolocation
    └── 🎤 Voice Recognition    # Speech-to-text processing
```

---

## 🛠️ Technology Stack

### **Frontend Framework**
- **React Native 0.79.5** - Cross-platform mobile development
- **Expo SDK 53** - Development platform and tools
- **Expo Router 5.1.3** - File-based navigation system

### **UI & Design**
- **React Native Vector Icons** - Icon library
- **Expo Linear Gradient** - Gradient effects
- **React Native Maps** - Interactive mapping
- **Custom Design System** - Consistent UI components

### **State Management**
- **React Context API** - Global state management
- **AsyncStorage** - Local data persistence
- **Expo Constants** - Environment configuration

### **Location & Maps**
- **Expo Location** - GPS and location services
- **React Native Maps** - Map visualization
- **Google Places Autocomplete** - Location search

### **Voice & Speech**
- **@react-native-voice/voice** - Voice recognition
- **Expo Speech** - Text-to-speech synthesis
- **Custom Voice Service** - Command processing

### **External Services**
- **OpenWeather API** - Weather data integration
- **Custom Backend API** - Traffic analytics backend
- **Real-time Communication** - WebSocket connections

### **Development Tools**
- **Expo CLI** - Development and build tools
- **Babel** - JavaScript transpilation
- **Metro Bundler** - React Native bundler

---

## 📱 Screenshots

<div align="center">

| Home Dashboard | Real-Time Map | Weather Integration |
|:---:|:---:|:---:|
| ![Home](assets/screenshots/home.png) | ![Map](assets/screenshots/map.png) | ![Weather](assets/screenshots/weather.png) |

| Voice Commands | Traffic Analytics | Route Planning |
|:---:|:---:|:---:|
| ![Voice](assets/screenshots/voice.png) | ![Analytics](assets/screenshots/analytics.png) | ![Routes](assets/screenshots/routes.png) |

</div>

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** (v18 or higher)
- **npm** or **yarn** package manager
- **Expo CLI** (`npm install -g @expo/cli`)
- **iOS Simulator** (for iOS development)
- **Android Studio** (for Android development)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/CONIA-Hackathon/front_end_trafficaz.git
   cd trafficaz-frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Configure environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your API keys
   ```

4. **Start the development server**
   ```bash
   npm start
   # or
   expo start
   ```

5. **Run on device/simulator**
   ```bash
   # iOS
   npm run ios
   
   # Android
   npm run android
   
   # Web
   npm run web
   ```

### Development Commands

```bash
# Start development server
npm start

# Run on specific platform
npm run ios
npm run android
npm run web

# Build for production
expo build:ios
expo build:android

# Eject from Expo (if needed)
expo eject
```

---

## ⚙️ Configuration

### Environment Variables

Create a `.env` file in the root directory:

```env
# Weather API Configuration
OPENWEATHER_API_KEY=your_openweather_api_key_here

# Backend API Configuration
BACKEND_API_URL=https://backend-traffic-detection-production.up.railway.app

# Google Maps API Key (for Android)
GOOGLE_MAPS_API_KEY=your_google_maps_api_key_here

# Voice Recognition Configuration
VOICE_RECOGNITION_LANGUAGE=en-US

# App Configuration
APP_ENV=development
DEBUG_MODE=true
```

### API Keys Setup

#### 1. OpenWeather API
1. Visit [OpenWeather API](https://openweathermap.org/api)
2. Sign up for a free account
3. Generate an API key
4. Add the key to your `.env` file

#### 2. Google Maps API (Optional)
1. Go to [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project
3. Enable Maps SDK for Android/iOS
4. Generate API keys
5. Add keys to your configuration

### Platform-Specific Setup

#### iOS Configuration
```json
// app.json
{
  "expo": {
    "ios": {
      "supportsTablet": true,
      "infoPlist": {
        "NSLocationWhenInUseUsageDescription": "TrafficAZ needs location access to provide real-time traffic updates.",
        "NSMicrophoneUsageDescription": "TrafficAZ uses microphone access for voice commands."
      }
    }
  }
}
```

#### Android Configuration
```json
// app.json
{
  "expo": {
    "android": {
      "adaptiveIcon": {
        "foregroundImage": "./assets/adaptive-icon.png",
        "backgroundColor": "#FF3951"
      },
      "permissions": [
        "ACCESS_FINE_LOCATION",
        "ACCESS_COARSE_LOCATION",
        "RECORD_AUDIO"
      ]
    }
  }
}
```

---

## 📖 API Documentation

### Backend API Endpoints

#### Traffic Data Submission
```http
POST /api/v1/locations/submit
Content-Type: application/json

{
  "userId": "user123",
  "latitude": 3.848033,
  "longitude": 11.502075,
  "speed": 25.5,
  "timestamp": "2024-01-15T10:30:00Z"
}
```

#### Traffic Analysis
```http
POST /api/v1/congestion/analyze
Content-Type: application/json

Response:
{
  "success": true,
  "data": [
    {
      "clusterId": "cluster_central_yaounde",
      "centroidLatitude": 3.848033,
      "centroidLongitude": 11.502075,
      "averageSpeed": 5.2,
      "userCount": 8,
      "detectedAt": "2024-01-15T10:30:00Z"
    }
  ]
}
```

#### Route Traffic Check
```http
POST /api/v1/congestion/route-check
Content-Type: application/json

{
  "startLatitude": 3.848033,
  "startLongitude": 11.502075,
  "endLatitude": 3.850000,
  "endLongitude": 11.504000,
  "routeRadius": 1000
}
```

### Weather API Integration

#### Current Weather
```javascript
// Get current weather for location
const weather = await weatherService.getCurrentLocationWeather();

// Response structure
{
  current: {
    temperature: 25,
    feelsLike: 27,
    humidity: 65,
    windSpeed: 12,
    description: "Partly cloudy",
    trafficImpact: {
      level: "medium",
      reasons: ["Light rain affecting visibility"],
      delayMinutes: 5
    }
  }
}
```

### Voice Recognition API

#### Voice Commands
```javascript
// Available voice commands
const commands = {
  'traffic_situation': ['traffic situation', 'how is traffic'],
  'report_traffic': ['report traffic', 'traffic report'],
  'check_alerts': ['check alerts', 'notifications'],
  'weather_info': ['weather', 'temperature'],
  'route_traffic': ['route traffic', 'my route']
};
```

---

## 🤝 Contributing

We welcome contributions from the community! Please read our contributing guidelines before submitting pull requests.

### Development Workflow

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Make your changes**
4. **Add tests** (if applicable)
5. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
6. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
7. **Open a Pull Request**

### Code Style Guidelines

- Follow **ESLint** configuration
- Use **Prettier** for code formatting
- Write meaningful commit messages
- Add JSDoc comments for functions
- Follow React Native best practices

### Testing

```bash
# Run tests
npm test

# Run tests with coverage
npm run test:coverage

# Run specific test file
npm test -- --testPathPattern=WeatherWidget
```

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **OpenWeather API** for weather data
- **Expo Team** for the amazing development platform
- **React Native Community** for continuous improvements
- **Cameroon Tech Community** for support and feedback

---

## 📞 Support

- **Email**: trafficaz@gmail.com
- **Documentation**: [docs.trafficaz.com](https://github.com/CONIA-Hackathon/front_end_trafficaz)
- **Issues**: [GitHub Issues](https://github.com/CONIA-Hackathon/front_end_trafficaz/issues)
- **Discord**: [TrafficAZ Community](https://discord.gg/trafficaz)

---

<div align="center">

**Made with ❤️ in Cameroon**

[![GitHub stars](https://img.shields.io/github/stars/your-username/trafficaz-frontend?style=social)](https://github.com/your-username/trafficaz-frontend)
[![GitHub forks](https://img.shields.io/github/forks/your-username/trafficaz-frontend?style=social)](https://github.com/your-username/trafficaz-frontend)
[![GitHub issues](https://img.shields.io/github/issues/your-username/trafficaz-frontend)](https://github.com/your-username/trafficaz-frontend/issues)

</div>

## BACKEND IMPLEMENTATION

# Traffic App Backend

A comprehensive FastAPI-based backend system for real-time traffic congestion detection and notification management. The system combines GPS-based clustering analysis with computer vision-based vehicle detection to provide accurate traffic insights.

## 🚀 Features

### Core Functionality
- **Real-time Traffic Analysis**: GPS-based congestion detection using DBSCAN clustering
- **Computer Vision Integration**: YOLOv8-based vehicle detection from traffic images
- **Multi-channel Notifications**: SMS, voice, and push notification support via Twilio
- **User Management**: Registration, authentication, OTP verification, and profile management
- **Webhook System**: Configurable webhooks for real-time event notifications
- **Location Tracking**: Real-time location submission and analysis
- **Voice Commands**: Voice-based interaction with the system

### Technical Features
- **FastAPI Framework**: High-performance async API with automatic documentation
- **PostgreSQL Database**: Robust data storage with SQLAlchemy ORM
- **Cloudinary Integration**: Cloud-based image storage and management
- **Alembic Migrations**: Database schema version control
- **JWT Authentication**: Secure token-based authentication
- **Comprehensive Testing**: Extensive test suite with Postman collection

## 🏗️ Architecture

### Project Structure
```
Backend/
├── app/
│   ├── api/                    # API endpoints
│   │   ├── users.py           # User management endpoints
│   │   ├── locations.py       # Location tracking endpoints
│   │   ├── congestion.py      # Congestion analysis endpoints
│   │   ├── camera_congestion.py # Image-based congestion detection
│   │   ├── notifications.py   # Notification management
│   │   ├── webhooks.py        # Webhook configuration
│   │   └── voice_commands.py  # Voice command processing
│   ├── core/                  # Core configuration
│   │   ├── config.py          # Environment configuration
│   │   └── security.py        # Security utilities
│   ├── db/                    # Database layer
│   │   ├── database.py        # Database connection
│   │   └── models.py          # SQLAlchemy models
│   ├── models/                # Pydantic schemas
│   │   └── schemas.py         # Request/response models
│   ├── services/              # Business logic
│   │   ├── user_service.py    # User management logic
│   │   ├── congestion_service.py # Congestion analysis
│   │   ├── yolo_service.py    # YOLO model integration
│   │   ├── notification_service.py # Notification handling
│   │   ├── webhook_service.py # Webhook management
│   │   ├── voice_service.py   # Voice command processing
│   │   ├── cloudinary_service.py # Image storage
│   │   └── location_service.py # Location processing
│   ├── utils/                 # Utility functions
│   │   ├── helpers.py         # General utilities
│   │   └── twilio_helper.py   # Twilio integration
│   └── main.py               # FastAPI application entry
├── alembic/                   # Database migrations
├── tests/                     # Test scripts
├── requirements.txt           # Python dependencies
├── postman_collection.json    # API testing collection
└── yolov8n.pt                # YOLOv8 pretrained model
```

### Database Schema

#### Core Tables
- **users**: User accounts with authentication and profile data
- **locations**: GPS location data for congestion analysis
- **congestion_events**: Detected traffic congestion clusters
- **image_analysis**: Camera-based congestion analysis results
- **notification_subscriptions**: User notification preferences
- **notification_history**: Notification delivery tracking
- **webhooks**: Webhook configuration and management
- **webhook_deliveries**: Webhook delivery history

## 🛠️ Technology Stack

### Backend Framework
- **FastAPI 0.115.14**: Modern, fast web framework for building APIs
- **Uvicorn 0.35.0**: ASGI server for running FastAPI applications
- **Pydantic 2.11.7**: Data validation and settings management

### Database
- **PostgreSQL**: Primary database
- **SQLAlchemy 2.0.41**: Python SQL toolkit and ORM
- **Alembic 1.16.2**: Database migration tool
- **asyncpg 0.30.0**: Async PostgreSQL driver

### Computer Vision
- **Ultralytics 8.3.162**: YOLOv8 implementation
- **PyTorch 2.7.1**: Deep learning framework
- **OpenCV 4.11.0.86**: Computer vision library
- **Pillow 11.3.0**: Image processing

### External Services
- **Twilio 9.6.4**: SMS and voice communication
- **Cloudinary 1.44.1**: Cloud image storage and management

### Security
- **bcrypt 4.3.0**: Password hashing
- **PyJWT 2.10.1**: JSON Web Token implementation
- **passlib 1.7.4**: Password hashing library

## 🚀 Deployment

### Prerequisites
- Python 3.8+
- PostgreSQL database
- Twilio account (for SMS/voice)
- Cloudinary account (for image storage)

### Environment Setup

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Backend
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   Create a `.env` file with the following variables:
   ```env
   DATABASE_URL=postgresql://username:password@localhost:5432/traffic_app
   SECRET_KEY=your_jwt_secret_key
   TWILIO_ACCOUNT_SID=your_twilio_account_sid
   TWILIO_AUTH_TOKEN=your_twilio_auth_token
   TWILIO_PHONE_NUMBER=your_twilio_phone_number
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   CLOUDINARY_FOLDER=traffic_app
   ```

5. **Database setup**
   ```bash
   # Run database migrations
   alembic upgrade head
   ```

6. **Start the server**
   ```bash
   uvicorn app.main:app --host 0.0.0.0 --port 8000 --reload
   ```

### Production Deployment

#### Using Docker
```dockerfile
FROM python:3.9-slim

WORKDIR /app
COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .
EXPOSE 8000

CMD ["uvicorn", "app.main:app", "--host", "0.0.0.0", "--port", "8000"]
```

#### Using Gunicorn
```bash
pip install gunicorn
gunicorn app.main:app -w 4 -k uvicorn.workers.UvicornWorker --bind 0.0.0.0:8000
```

## 📊 API Endpoints

### User Management
- `POST /api/v1/users/register` - User registration
- `POST /api/v1/users/login` - User authentication
- `POST /api/v1/users/send-otp` - Send OTP for verification
- `POST /api/v1/users/verify-otp` - Verify OTP code
- `GET /api/v1/users/profile` - Get user profile

### Location Tracking
- `POST /api/v1/locations/submit` - Submit location data

### Congestion Analysis
- `POST /api/v1/congestion/analyze` - Analyze GPS-based congestion
- `GET /api/v1/congestion/status/{cluster_id}` - Get congestion status
- `POST /api/v1/congestion/image-upload` - Upload image for analysis
- `POST /api/v1/congestion/image-upload-pretrained` - Upload image with pretrained model
- `GET /api/v1/congestion/model-info` - Get YOLO model information

### Notifications
- `POST /api/v1/notifications/subscribe` - Subscribe to notifications
- `POST /api/v1/notifications/send` - Send manual notification

### Webhooks
- `POST /api/v1/webhooks/configure` - Configure webhook
- `GET /api/v1/webhooks/list` - List webhooks
- `PUT /api/v1/webhooks/{webhook_id}/toggle` - Toggle webhook status
- `GET /api/v1/webhooks/deliveries` - Get delivery history

### Voice Commands
- `POST /api/v1/voice-commands/process` - Process voice commands

## 🧪 Testing

### Quick Start Testing

1. **Start the server**
   ```bash
   uvicorn app.main:app --reload
   ```

2. **Access API documentation**
   - Swagger UI: http://localhost:8000/docs
   - ReDoc: http://localhost:8000/redoc

3. **Import Postman collection**
   - Import `postman_collection.json` into Postman
   - Set environment variables in Postman:
     - `base_url`: `http://localhost:8000`
     - `phone_number`: Your test phone number
     - `user_id`: (auto-filled after registration)
     - `webhook_id`: (auto-filled after webhook creation)

### Testing Flow

1. **User Registration & Authentication**
   ```bash
   # Register a new user
   POST /api/v1/users/register
   
   # Send OTP for verification
   POST /api/v1/users/send-otp
   
   # Verify OTP
   POST /api/v1/users/verify-otp
   ```

2. **Location Submission**
   ```bash
   # Submit location data (requires multiple users for congestion detection)
   POST /api/v1/locations/submit
   ```

3. **Congestion Analysis**
   ```bash
   # Analyze GPS-based congestion
   POST /api/v1/congestion/analyze
   
   # Upload traffic image for analysis
   POST /api/v1/congestion/image-upload-pretrained
   ```

4. **Webhook Configuration**
   ```bash
   # Configure webhook (get URL from webhook.site)
   POST /api/v1/webhooks/configure
   ```

5. **Notification Testing**
   ```bash
   # Subscribe to notifications
   POST /api/v1/notifications/subscribe
   
   # Send test notification
   POST /api/v1/notifications/send
   ```

### Test Scripts

The `tests/` directory contains various test scripts:
- `test_congestion_data.py` - Test congestion detection
- `test_notifications.py` - Test notification system
- `test_webhook_system.py` - Test webhook functionality
- `test_verified_user_notification.py` - Test user verification flow

## 🔧 Configuration

### Congestion Detection Settings
- **DBSCAN Parameters**: 
  - `eps`: 0.025 (2.5km radius)
  - `min_samples`: 2 (minimum users for congestion)
- **Speed Threshold**: 20 km/h (below this triggers congestion analysis)
- **Vehicle Detection**: YOLOv8 pretrained model with 80 classes

### Notification Settings
- **SMS**: Via Twilio
- **Voice**: Via Twilio
- **Radius**: Configurable alert radius (default: 2km)
- **Do Not Disturb**: Configurable time windows

### Webhook Settings
- **Retry Count**: 3 attempts
- **Timeout**: 30 seconds
- **Event Types**: congestion_detected, image_analyzed

## 📈 Performance

### Optimization Features
- **Async Operations**: All database and external API calls are async
- **Connection Pooling**: Database connection pooling for better performance
- **Image Caching**: Cloudinary integration for efficient image storage
- **Batch Processing**: Efficient handling of multiple location submissions

### Monitoring
- **Health Checks**: Built-in health check endpoints
- **Error Logging**: Comprehensive error tracking
- **Performance Metrics**: Request/response timing

## 🔒 Security

### Authentication & Authorization
- **JWT Tokens**: Secure token-based authentication
- **Password Hashing**: bcrypt for secure password storage
- **OTP Verification**: Two-factor authentication via SMS
- **Input Validation**: Pydantic models for request validation

### Data Protection
- **Environment Variables**: Sensitive data stored in environment variables
- **HTTPS**: Production deployment with SSL/TLS
- **Input Sanitization**: All user inputs are validated and sanitized

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🆘 Support

For support and questions:
- Check the API documentation at `/docs`
- Review the Postman testing guide
- Check the test scripts in the `tests/` directory
- Review the detailed documentation files:
  - `POSTMAN_TESTING_GUIDE.md`
  - `WEBHOOK_DOCUMENTATION.md`
  - `CLOUDINARY_INTEGRATION.md`
  - `USER_PROFILE_ENDPOINT.md`

## 🔄 Version History

- **v1.0.0**: Initial release with GPS-based congestion detection
- **v1.1.0**: Added YOLOv8 image-based congestion detection
- **v1.2.0**: Integrated webhook system and enhanced notifications
- **v1.3.0**: Added voice commands and user profile management
- **v1.4.0**: Switched to pretrained YOLOv8 model for better accuracy


## DATA TRAINING

Jupyter Notebook: https://colab.research.google.com/drive/1WDIlCm4wLpwS_TyL_gEHNwMMUuSSW0gU?usp=drive_link
