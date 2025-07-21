# FitMind: A Holistic Fitness and Mental Wellness App

**Live App:** [https://welness-6b05a.web.app](https://welness-6b05a.web.app)

## FitMind Overview

FitMind is a comprehensive fitness and mental wellness mobile-first web app built with Flutter and Firebase. The platform merges physical health, mental clarity, and social accountability into a single experience.

It is designed to guide users through structured workouts, provide mental well-being resources, track nutritional data, and foster a like-minded community.

---

##  Screenshots

<img width="1359" height="621" alt="Screenshot 2025-07-21 132806" src="https://github.com/user-attachments/assets/6535b604-d906-4f73-a4df-5a9938249b42" />

![Workout Player](screenshots/workout.png)
![Mental Wellness Section](screenshots/mental.png)
![Community Forum](screenshots/community.png)

---

##  Features

### Fitness Features

* Browse categorized workouts (Yoga, HIIT, Strength, Stretching)
* Video-based tutorials with embedded YouTube support
* Calorie estimation per workout
* Schedule and complete daily fitness challenges

### Mental Wellness

* Daily affirmations and mood check-ins
* Guided meditation sessions (YouTube embedded)
* Mental health blog integration
* Emotion tracking with visual trends

###  Community

* Anonymous message board for users to share progress
* Encouragement badges and emojis
* Commenting and upvoting system for accountability
* Firebase Firestore-powered real-time updates

### Nutrition + Calorie Tracker

* Basic calorie counter integration
* Educational tips on portion control
* Daily nutrition goals

### Cross-platform

* Fully responsive (Mobile-first)
* Built in Flutter Web + Firebase Hosting

---

## Tech Stack

| Layer    | Technology                          |
| -------- | ----------------------------------- |
| Frontend | Flutter (Web)                       |
| Backend  | Firebase (Firestore, Auth, Hosting) |
| Media    | YouTube Embeds                      |
| Hosting  | Firebase Hosting                    |
| Auth     | Firebase Auth                       |

---

##  Project Planning & Technical Architecture

FitMind was developed using an iterative, prompt-first design methodology. The project followed a structured planning phase involving:
* User flow mapping to define the experience from onboarding to daily tracking
* Modular architecture design for scalable feature integration (e.g., mental wellness, nutrition, fitness tracking)
* Firebase-first backend strategy for real-time data syncing and secure authentication
* UI prototyping and review cycles to refine user interactions and accessibility across screens

---

##  Local Setup

### 1. Prerequisites

* Flutter SDK
* Firebase CLI

### 2. Clone the Repo

```bash
git clone https://github.com/your-username/final-project.git
cd fitmind
```

### 3. Configure Firebase

* Connect to Firebase: `firebase use --add`
* Set the correct alias (e.g., `prod`)
* Ensure correct `firebase.json` points to `build/web`

### 4. Build and Deploy

```bash
flutter build web
firebase deploy
```

---

##  Security & Fault Tolerance

* Firebase Auth for secure login
* Anonymous mode supported
* Firestore security rules to protect write access
* Image URLs and content sanitized

---

##  Sample Test Cases

###  1. Workout Player Test

**Steps:**

* Navigate to a workout category
* Click a workout video
* Confirm calorie data displays and plays without errors

###  2. Mental Wellness Tool Test

**Steps:**

* Open Mental tab
* Select "Start Breathing Exercise"
* Observe animations and timers function properly

###  3. Community Test

**Steps:**

* Post a message anonymously
* React to another post
* Confirm changes reflect in real time

---

##  Future Roadmap

* [ ] AI-generated workouts
* [ ] Personalized nutrition suggestions
* [ ] Streak-based motivation system
* [ ] OAuth support for Google/Apple login

---

##  Contributors

* **Debrajoy Kitet** — Product Lead, Firebase Setup, Deployment, UI Design

---

##  License

This project is licensed under the MIT License.

---

##  Let’s Connect!

Built with 💚 for those who believe fitness and mental wellness are two sides of the same coin.

---

> "A healthy body supports a healthy mind—and a strong community keeps both resilient."
