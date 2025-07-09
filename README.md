# 🎮 GameVault – Game Account Marketplace

GameVault is a simple web-based platform where users can register, post game accounts for sale, upload images and videos, and securely sell their login info only after buyer confirmation.

---

## 🚀 Features

- 🔐 Firebase Authentication (Login/Register)
- 📝 Post game accounts with:
  - Title, Description, Price
  - Multiple required images
  - Optional video
  - Contact Email and Phone (required)
  - Private login info (shown only after purchase)
- 💼 Dynamic listings with:
  - Scrollable image gallery
  - Embedded video
  - Secure “Buy Now” system
- ☁️ Firebase Firestore + Storage integration
- ✨ All-in-one single HTML file — no backend required

---

## 📁 Project Structure

This is a single-file HTML app that includes:
- HTML markup
- CSS styling
- JavaScript logic
- Firebase SDKs

No separate files or frameworks are needed.

---

## 🛠️ Firebase Setup (Required)

1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new project
3. Enable **Authentication > Email/Password**
4. Create Firestore Database (in test mode)
5. Enable **Firebase Storage**
6. Replace your Firebase config inside this code block:

```js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
