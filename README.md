# 🌿 Eco Travel Mate – Your AI-Powered Sustainable Living Companion

> 🚀 Built for **Green Spark Hackathon 2025**
> 🔗 [Live Preview](https://joemartinrince.github.io/Eco-/) (Please update if the live preview changes with new features)

[![Hackathon](https://img.shields.io/badge/Hackathon-Green%20Spark%202025-orange)](https://github.com/Christwin-Soy-Jose/eco-travel-mate)
[![Platform](https://img.shields.io/badge/Platform-Flutter%20%2B%20Firebase-blue)](https://flutter.dev)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 🎯 Problem Statement

Unmindful daily habits, particularly short-distance trips and conventional travel choices, are significant contributors to:
- 🌍 **Increased Carbon Emissions:** Accelerating climate change and environmental degradation.
- 🚶 **Lifestyle-Related Health Issues:** Due to reduced physical activity.

A widespread lack of **awareness**, combined with the absence of **real-time feedback** and **actionable insights**, prevents many individuals from adopting more sustainable and healthier lifestyle choices.

---

## 🌱 Solution: Eco Travel Mate

**Eco Travel Mate** is an innovative, AI-powered mobile application designed to empower individuals to make greener choices in their daily lives and travel. By providing intelligent insights and motivation, the app aims to foster sustainable habits.

It achieves this by:
-   **Automatically detecting travel modes** and calculating carbon footprint.
-   **Suggesting eco-friendly alternatives** based on personalized data.
-   **Motivating users** through gamification and community engagement.
-   **Offering tools** for manual carbon footprint calculation, real-time air quality monitoring, and an AI-driven travel assistant for comprehensive eco-insights.

---

## 🧩 Core Features

### 🚶 Smart Travel Detection
Automatically identifies your mode of transport:
-   Walking
-   Cycling
-   Car
-   Public Transport

Powered by sophisticated GPS and motion activity data, ensuring seamless and accurate tracking without manual input.

---

### ♻️ Real-Time & Advanced CO₂ Emissions Calculator
Calculates your environmental impact for every trip, whether automatically detected or manually entered:

> ✅ **Example (Automatic):**
> Car (2 km) → ~0.5 kg CO₂
> Walk (2 km) → 0 kg CO₂ and 75 kcal burned!

> ✅ **Example (Manual Input):**
> Car (23 km) → ~3.91 kg CO₂ ≈ plant 1 tree.

---

### 🌿 Greener Suggestion Engine
Provides personalized, eco-friendly travel alternatives with compelling motivation:

> *"You could’ve saved 0.5 kg CO₂ and burned 75 kcal by walking this 2 km trip. Choose green next time!"*

---

### 🧠 AI Travel Assistant
Your intelligent companion for all eco-travel inquiries. Ask anything about sustainable travel options, eco-friendly destinations, tips for reducing your carbon footprint, and more, powered by cutting-edge AI.

---

### 💨 Air Quality Monitor
Access real-time Air Quality Index (AQI) data for various cities, with a special focus on Indian cities. This feature helps users make informed decisions about outdoor activities and choose healthier routes.

---

### 🎮 GreenPoints & Weekly Challenges
-   Earn **GreenPoints** for every eco-conscious action taken within the app.
-   Participate in **Weekly Challenges** to push your sustainable efforts further:
    > *"Replace 2 car trips with walks this week and earn bonus GreenPoints!"*

---

### 👨‍👩‍👧‍👦 Family Groups & Leaderboards
-   Form or join groups with family and friends to encourage collective action.
-   Compete for the top spot on **GreenScores** leaderboards.
-   Build eco-friendly habits together as a community 💚.

---

## 🛠 Tech Stack

| Layer             | Technology                                                |
|-------------------|-----------------------------------------------------------|
| **Frontend** | Flutter (Dart)                                            |
| **Backend** | Firebase (Authentication, Firestore, Cloud Functions), Flask |
| **Location** | GPS, Geolocator, Google Activity Recognition API          |
| **AI & Logic** | CO₂ emission calculator, Travel-mode classifier           |
| **AI Assistant** | (Specify if you used a particular LLM API like Gemini, OpenAI, etc., or custom NLP solution) |
| **Air Quality Data** | (Specify if you used a particular AQI data provider API or custom data source) |
| **Mapping** | Google Maps SDK / Mapbox                                  |
| **Gamification** | Custom points system, challenges, leaderboards            |

---

## 📱 Screenshots (Demo)

> All screenshots are located in the `assets/screenshots/` folder.

| Feature                      | Description                                        | Preview                                                   |
|------------------------------|----------------------------------------------------|-----------------------------------------------------------|
| 🏠 Home Screen               | GreenScore, trip summary, eco tips                 | ![](assets/screenshots/home_screen.png)                   |
| 📊 Trip Log                  | Detailed trip history and CO₂ impact               | ![](assets/screenshots/trip_log.png)                      |
| 💡 Suggestions               | Smart travel alternatives                          | ![](assets/screenshots/suggestion.png)                    |
| 🏆 Leaderboard               | Compete with friends/family                        | ![](assets/screenshots/leaderboard.png)                   |
| 🤖 AI Travel Assistant       | Intelligent Q&A for eco-travel queries             | ![](assets/screenshots/ai_travel_assistant.jpeg)          |
| 💨 Air Quality Monitor       | Real-time AQI for cities and interactive map       | ![](assets/screenshots/air_quality_indian_cities.jpeg)    |
| 📊 Carbon Calculator (Input) | Manual carbon footprint calculation input interface | ![](assets/screenshots/carbon_calculator_100km.jpeg)      |
| 📈 Carbon Calculator (Result)| Display of calculated emissions and eco-equivalents | ![](assets/screenshots/carbon_calculator_23km.jpeg)       |

---

## 🚀 Getting Started Locally

To get Eco Travel Mate up and running on your local machine, follow these steps:

```bash
# 1. Clone the repository
git clone [https://github.com/Christwin-Soy-Jose/eco-travel-mate.git](https://github.com/Christwin-Soy-Jose/eco-travel-mate.git)
cd eco-travel-mate

# 2. Install Flutter dependencies
flutter pub get

# 3. Setup Firebase
# Ensure you have a Firebase project configured.
# Add your `google-services.json` (for Android) or `GoogleService-Info.plist` (for iOS)
# files to their respective platform directories.

# 4. Run the application
flutter run
