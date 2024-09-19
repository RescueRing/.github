
# Team Rescue Ring: Disaster Management Solution

Welcome to **Rescue Ring**, an innovative disaster management solution created for the **Smart India Hackathon**. Our platform provides seamless communication, real-time alerts, and resource coordination during natural disasters, combining the power of a **mobile app**, **website**, and **ovos voice assistance** to help communities stay prepared and connected.

---
### Download APK

<a href="https://github.com/RescueRing/resources/raw/refs/heads/main/app/apk_file/app-release.apk">
<img src="https://camo.githubusercontent.com/2b0b605d77141fd0ff5f5aa8159f6121c4d4bd213d5ee2aba1753d678faaf28c/68747470733a2f2f692e6962622e636f2f71306d6463345a2f6765742d69742d6f6e2d6769746875622e706e67" width=350/>
</a>




---

## Table of Contents
- [Introduction](#introduction)
- [Key Features](#key-features)
  - [App Features](#app-features)
  - [Website Features](#website-features)
  - [Voice Assistance](#voice-assistance)
  - [Volunteer System](#volunteer-system)
- [Technology Stack](#technology-stack)
- [Important Repository](#important-repositories)
- [License](#license)

---

## Introduction

**Rescue Ring** is a disaster management solution designed to help people and communities efficiently handle natural disasters. The system integrates a mobile app, website, and Voice assistance to provide real-time disaster updates, resource requests, and community support. Our app is focused on **quick communication**, **volunteer mobilization**, and **life-saving resources** when disasters strike.

This project focuses on three core aspects:
1. **Educating** the public about disaster preparedness and government schemes.
2. **Facilitating communication** between users during disasters through a dynamic map-based interface.
3. Offering a **volunteer-driven system** to ensure proper validation of disaster reports and direct support to affected individuals.

**Important**: This project is developed as part of the **Smart India Hackathon**, and its source code and features are restricted for use.

---

## **Key Features**

### **1. Website**

The **Rescue Ring Website** serves as an educational hub that:
- **Educates** users about various types of disasters and how to prepare for them.
- Lists **government schemes** with clear instructions on how to apply and benefit.
- Provides a **centralized platform** for accessing disaster resources and preparedness guides.

### **2. Mobile App**

The **Rescue Ring Mobile App** (available on **Android and iOS**) is designed for:
- **Real-time disaster communication** through a **Google Maps-powered interface**.
- **SOS messaging** to emergency contacts during critical situations.
- Quick and **concise disaster preparedness** guides.
- **Resource sharing** (food, shelter, medical aid) with the ability to mark locations on the map.
- **Multilingual support** for a wider audience.
- **Volunteer functionality** for community support and disaster verification.

### **3. Voice assistance**

The **Rescue Ring Voice assistance** is a smart speaker that:
- **Broadcasts real-time alerts** during disasters.
- Provides **critical disaster information** audibly, ensuring that people remain informed even when their hands are occupied.
---

## Core Features

### App Features

1. **Real-Time Communication via Google Maps**  
   - Users can report disasters, request resources (medicine, food, shelter), and view affected areas through a heatmap **visualizes affected zones**, aiding effective response.
   
2. **Emergency Contacts & SOS Messaging**  
   - Save **emergency contacts** and send **SOS messages** in one tap during an emergency situation.
   
3. **Disaster Education**  
   - **Concise guides** on how to prepare for different disasters. The information is kept simple for quick reference during emergencies.
   - Short and crisp guides for various natural disasters, covering **do's and don'ts** during emergencies.
   - Quick access to key information without overwhelming users in critical moments.

4. **Government Schemes Information**  
   - A comprehensive list of **government schemes** related to disaster relief, including who can apply and how to apply.
   - Simple, step-by-step guidance for **eligibility** and **application** procedures.
   - Dynamically add new government schemes based on locations, if the location is effected by any chance.

5. **Multilingual Support**  
   - **Seamless language switching** to cater to users from different regions, ensuring accessibility.

6. **Volunteer Program**  
   - Volunteers are given additional functionality, such as the ability to **verify disaster reports**, **send alerts**, and **moderate community resources**.

7. **Disaster Mode**:
   - Once a disaster is confirmed, the app switches to **Disaster Mode**, transforming the UI to prioritize essential information and emergency actions.
   - **Preparedness guidance**, **critical alerts**, and **SOS** options are made readily available.


### Website Features
- A well-organized hub providing educational resources on **disaster preparedness**, **government schemes**, and **recovery steps**.
- Centralized information on government aid and **relief programs**, ensuring people are well-informed.
- Easy-to-navigate platform, designed to spread awareness and equip people with necessary knowledge before disasters.

### Voice Assistance
- **Voice alerts** broadcast critical information about upcoming or ongoing disasters.
- Guides individuals on **preparedness steps**, ensuring awareness without needing to access the app or website.
 
---

## Volunteer System

### **Special Features for Volunteers**: 
**Special benefits** for volunteers who play a crucial role in disaster response:
- **Exclusive functionalities** like editing **map markers**, managing the **heatmap** for affected areas, and sending **push notifications** to alert users.
- **Verify Reports**: Volunteers can confirm the authenticity of disaster reports before alerts are sent out to the community.
- **Send Push Notifications**: Volunteers can send **emergency notifications** to users in the affected area.
- **Ban Spammers**: Volunteers can ban users who falsely report disasters or spam the platform.

#### Volunteer Signup Process
1. Educate volunteers about the app's goals and benefits.
2. List volunteer **responsibilities** and terms to ensure ethical use of the platform.
3. Volunteers sign up by providing personal information and selecting from a list of **12 key skills** (e.g., **first aid**, **swimming**, **boating**), which will be used for assigning roles during rescue operations.
4. Admin verification before volunteers gain access to exclusive features.

---
## App "**Disaster Mode**"
### Disaster Mode Features

- **Simplified Interface:** The app's UI is transformed to prioritize essential features during a disaster.
  - **SOS Button:** Allows users to send emergency messages to their loved ones in one tap.
  - **Heatmap of Affected Areas:** Displays real-time information on impacted regions.
  - **Resource Requests/Offers:** Enables users to request or offer help for essential resources.
  - **Live Updates:** Provides continuous updates on the disaster situation.
- **Front-Loaded Emergency Tools:** Emergency contacts and survival checklists are moved to the forefront for quick access.
- **Preparedness Guidance:** Displays critical preparedness information and survival tips to help users stay safe.
- **Battery Saver Mode:** Automatically activates to conserve phone battery during emergencies.
- **Volunteer Control:** Volunteers are given enhanced features, such as the ability to send push notifications to users and verify disaster reports.
- **User Alerts:** A visible alert is shown to all users to signal the activation of Disaster Mode and provide immediate guidance.

## Technology Stack

- **Mobile App**: 
  - Framework: **Flutter**
  - Language: **Dart**
  - Real-time database: **Firebase Firestore**
  - Notifications: **Firebase Messaging**
  
- **Web Platform**:
  - Language: **Typescript**
  - Backend: **Node.js**
  - Framework: **Next.js**
  - Desiging: **TailwindCSS**
  
- **Voice Assistance**:
  -    Language: **Python**
  - Framework: **ZeroMQ**

  
- **Firebase** for Authentication, Push notification and Real-time updates.

---

## Important Repositories

Below are the key repositories for the **Team Rescue Ring** project:

1. **Flutter App (Disaster Management App)**  
   - GitHub Repository: [Disaster Management App](https://github.com/RescueRing/disaster-ready)
   - Platform: **Flutter (Android & iOS)**  
   - Description: The mobile app helps users communicate during disasters, report affected areas, and request or offer assistance.  
   - [Download APK](https://github.com/RescueRing/resources/raw/refs/heads/main/app/apk_file/app-release.apk)

2. **Website (Disaster Awareness Portal)**  
   - GitHub Repository: [Disaster Awareness Website](https://github.com/RescueRing/disaster-ready-website)
   - Hosted Link: [Visit the Website](https://disaster-ready-website.vercel.app)
   - Description: A web-based platform to educate people about disaster preparedness, government schemes, and recovery steps.




## License 
Copyright (c) 2024 Team Rescue Ring

All rights reserved. This project is licensed under the following terms: 
- This software is provided "as is" and any express or implied warranties, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose, are disclaimed.
- Redistribution, modification, and commercial use of this project are strictly prohibited.


