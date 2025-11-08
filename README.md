# 🎥 Strangers Video Calling App

A **real-time video chat application** that connects users randomly for live one-on-one video calls.  
The app features a **coin-based credit system** that encourages continuous engagement, allowing users to earn coins by watching ads and spend them during video calls.

---

## 🚀 Features

- 🔹 **Real-Time Video Calling:** Instantly connect with random users using **WebRTC** for smooth peer-to-peer video sessions.  
- 🔹 **Coin-Based System:** Each call deducts a fixed number of coins from the user's wallet to manage engagement.  
- 🔹 **Earn Coins by Watching Ads:** Integrated **Google AdMob** for rewarded ads to let users earn more coins.  
- 🔹 **Secure & Anonymous:** Maintains user privacy with secure **Firebase Authentication** and anonymous connections.  
- 🔹 **Engaging UI/UX:** Built with **Android XML layouts** for a responsive, intuitive experience.

---

## ⚙️ How It Works

1. **Start a Call:** Launch the app and get matched with a random online user.  
2. **Spend Coins:** Each active video call deducts coins from the user’s balance.  
3. **Earn More Coins:** Watch ads via **AdMob** to earn free coins and continue chatting.  
4. **Enjoy Conversations:** Meet new people and enjoy seamless, real-time video interactions.

---

## 🛠️ Tech Stack

| Layer | Technology |
|--------|-------------|
| **Frontend** | Android (Java, XML) |
| **Backend** | Firebase + WebRTC |
| **Database** | Firestore |
| **Monetization** | Google AdMob |
| **Authentication** | Firebase Auth |

---

## 🧩 Architecture Overview

```mermaid
flowchart TD
    A["User 1"] -->|"Connect via WebRTC"| B["Signaling Server (Firebase)"]
    B --> C["User 2"]
    A --> D["Firestore Database"]
    C --> D
