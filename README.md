# 📱 QSplit Android APK
---

A mobile-ready Android adaptation of the original QSplit web application using Capacitor and Android Studio.

QSplit fairly distributes shared discounts based on how much each person spent.
For example, if a Rs.500 offer is unlocked by a total order above Rs.2000, the discount is proportionally divided instead of equally split ensuring the person who spent more receives a fairer share of the discount.

## 🌐 Original Project
---

Original web application developed by [Lawsan](https://www.lawsan.dev/):

https://github.com/lawsanm/qsplit

Web version:

https://qsplit.vercel.app/

## 🛠 My Contribution
---

Android adaptation and customization by Janagan.

## ✅ Added Features & Changes
---

- Integrated Capacitor for Android support
- Converted the React/Vite web app into an installable Android APK
- Configured Android Studio project setup
- Added Android launcher icons
- Configured Vite asset loading for APK compatibility
- Added native Android build workflow
- APK signing and release setup

## ⚙️ Technologies Used
---

- React
- Vite
- Capacitor
- Android Studio
- Tailwind CSS
- JavaScript

## 🚀 Run Locally
---

### 1. Clone Repository

```bash
git clone https://github.com/janagan2k04/Qsplit-android.git
cd Qsplit-android
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start Development Server

```bash
npm run dev
```

The app will run locally at:

```text
http://localhost:5173
```

## 📦 Build Android APK

### 1. Build Web Assets

```bash
npm run build
```

### 2. Sync Capacitor

```bash
npx cap sync
```

### 3. Open Android Studio

```bash
npx cap open android
```

### 4. Generate APK

Inside Android Studio:

```text
Build → Generate Signed Bundle / APK
```

Choose:

```text
APK
```

Then create/select your keystore and build the release APK.

## 📁 Important Notice
---

This repository contains:
- React source code
- Capacitor Android integration
- Android Studio project files
- APK build configuration
- **Release APK file (android\app\release\app-release.apk)**

This repository does NOT include:
- node_modules
- signing keystores (.jks)

## ❤️ Credits
---

Designed and originally developed by [Lawsan](https://www.lawsan.dev/).

Android adaptation, APK integration, customization and Android deployment made by [Janagan](https://www.linkedin.com/in/janagan2k04/).

**Last but not least big thanks to ChatGPT for guidance**