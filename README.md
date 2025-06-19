# StepBet 🚶💰

StepBet is a Kotlin-based Android fitness app that lets users bet real money on their daily step goals. If the user completes the step challenge within 24 hours, they win back their stake with a reward!

<div align="center">
  <img src="stepbet_images/stepBet_challenge.jpg" alt="Step Goal and Stake Challenge" width="250"/>
  <img src="stepbet_images/stepBet_home.jpg" alt="Home Dashboard" width="250"/>
  <img src="stepbet_images/stepbet_profile.jpg" alt="Profile Page" width="250"/>
  <img src="stepbet_images/stepbet_wallet.jpg" alt="Wallet Transactions" width="250"/>
</div>

---

## 🔑 Features

- ✅ **Login/Signup with OTP (Firebase Authentication)**
- 🏃 **Step Challenge System:** Set a 24-hour step goal and stake amount
- 💰 **Real Money Staking and Rewards**
- 💳 **Razorpay Integration** for:
  - Adding money
  - Withdrawing earnings
- 📈 **Step Tracker Dashboard**
- 📊 **Profile Statistics:**
  - Success Rate
  - Challenge Count
  - Total Earnings
- 🔁 **Transaction History & Wallet Overview**

---

## ⚙️ Tech Stack

| Technology      | Purpose                                |
|------------------|----------------------------------------|
| Kotlin           | Native Android development             |
| Firebase Auth    | OTP-based user login/sign-up           |
| Firebase Firestore | Backend database for challenges, users |
| Razorpay         | Real money transactions (Add/Withdraw) |
| Step Counter API | Counting daily physical steps          |

---

## 🖼 Screenshots

### 1. Create Challenge Screen
Shows user-set goal and custom stake amount:
![Create Challenge](stepbet_images/stepBet_challenge.jpg)

### 2. Home Screen
Live step counter and quick challenge setup:
![Home Dashboard](stepbet_images/stepBet_home.jpg)

### 3. Profile Screen
Track success rate, total earnings, and challenges:
![Profile](stepbet_images/stepbet_profile.jpg)

### 4. Wallet Screen
Track transactions, wallet balance, add/withdraw money:
![Wallet](stepbet_images/stepbet_wallet.jpg)

---

## 🚀 Getting Started

### Prerequisites

- Android Studio Flamingo or newer
- Firebase project with:
  - Authentication (Phone)
  - Firestore Database
- Razorpay account & API keys
- Internet & step counter permission in AndroidManifest

### Installation

```bash
git clone https://github.com/DevDatir/StepBet.git
