# Railway Guider Admin Mobile App

![GitHub repo size](https://img.shields.io/github/repo-size/dileepadev/railway-guider-admin?color=red&label=repository%20size)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/dileepadev/railway-guider-admin?color=red)
![GitHub language count](https://img.shields.io/github/languages/count/dileepadev/railway-guider-admin)
![GitHub top language](https://img.shields.io/github/languages/top/dileepadev/railway-guider-admin)
![GitHub](https://img.shields.io/github/license/dileepadev/railway-guider-admin?color=yellow)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/dileepadev/railway-guider-admin?color=brightgreen&label=commits)

## ✨ About

The **Railway Guider Admin** mobile app is the admin mobile app for Railway Guider project. With this admin app, Train drivers can manage locations and add or remove locations manually or automatically. Every admin app is built for a specific train, and this app allows to view the currently booked passengers and passengers on the train. Passengers can be notified by SMS about the current train or train situation. This alpha release does not include the complete requirements and interface. **This project has been developed as an open source for educational purposes.**

![Preview Image](https://dileepadev.github.io/images/railway-guider-admin/preview.png)

## 🎞️ Demo Video

Click the link or image below to view the demo video on YouTube.

🔗 <https://youtu.be/waE9ZqxgTUo>

[![Watch the demo video](https://img.youtube.com/vi/waE9ZqxgTUo/0.jpg)](https://youtu.be/waE9ZqxgTUo)

## 📦 Release Details

Release Version - 1.0.0  
Initial release date - July 3, 2020

> [!NOTE]
> This repository is a clean re-upload to my new GitHub account. No new features or functionality have been added. Minor compatibility fixes may have been applied to ensure the project runs correctly in the current environment. Please note that the original commit history from the previous account is not preserved. This update is primarily for migration purposes.
>
> **Initial release date:** July 3, 2020  
> **Migration date:** December 28, 2025  
> **Last review date:** December 31, 2025

## 💡 Deployment

Deployment is not currently in use

## 💻 Built with

- Java
- Android
- Firebase
- Android Studio

## 📌 Prerequisites

Before you get started, follow these requirements.

### Legacy (original)

- Firebase project
- Google Maps API key
- Java 8 (1.8)
- Android compileSdkVersion 28 (Android 9.0 Pie)
- minSdkVersion 21
- Android Build Tools 29.0.2
- Android Gradle Plugin (AGP) 3.6.1
- Gradle 5.6.4

### Upgraded / Recommended

- Firebase project
- Google Maps API key
- Java 17 (or latest LTS)
- Android Gradle Plugin (AGP) 7.4.0
- Gradle 8.13

Notes:

- When upgrading AGP/Gradle, update the Gradle wrapper and follow AGP compatibility docs.
- Verify compileSdkVersion and build tools match libraries you use after upgrade.
- Keep google-services.json and Maps API configuration unchanged when upgrading.

## 🍃 How to Setup

- Download or clone the repository
- Move the project to the selected directory
- Create firebase project
- Create google maps API
- Open with Android Studio
- Add firebase file `(google-services.json)` and sync
- Add google maps API to these location:
  - debug: [app/src/debug/res/values/google_maps_api.xml](/app/src/debug/res/values/google_maps_api.xml)
  - release: [app/src/release/res/values/google_maps_api.xml](/app/src/release/res/values/google_maps_api.xml)
- Change the package name if necessary
- Clean project and rebuild project
- Do not update / upgrade gradle and other versions until the app is up and running with built versions

## 🚀 How to Run

- Clean and build the project
- Launch AVD
- Run on the emulator

## 📸 Icons and Images

- Icons8 - <https://icons8.com>
- Freepik - <https://www.freepik.com>
- unDraw - <https://undraw.co>
- Railway images are downloaded from Google

## 💎 Dependencies

- Paper - <https://github.com/pilgr/Paper>
- AndroidX AppCompat - <https://developer.android.com/jetpack/androidx/releases/appcompat>
- ConstraintLayout - <https://developer.android.com/jetpack/androidx/releases/constraintlayout>
- Google Play Services (Maps) - <https://developers.google.com/maps/documentation/android-sdk/overview>
- Firebase Realtime Database - <https://firebase.google.com/docs/database>
- Firebase Analytics - <https://firebase.google.com/docs/analytics>
- RecyclerView - <https://developer.android.com/jetpack/androidx/releases/recyclerview>
- CardView - <https://developer.android.com/jetpack/androidx/releases/cardview>
- Material Components - <https://material.io/develop/android>
- JUnit (test) - <https://junit.org/junit4/>
- AndroidX Test & Espresso (androidTest) - <https://developer.android.com/training/testing/espresso>

## ❤️ Thanks

Thanks to everyone who supported

## 👨‍💻 Developed By

Dileepa Bandara  
[@dileepadev](https://github.com/dileepadev)  
<https://dileepa.dev>

> [!NOTE]
> This repository may contain references to my former GitHub username (`dileepabandara`) and domain (`dileepabandara.dev`), which I no longer use. These identifiers may now belong to other parties. All current development and maintenance are conducted under my new GitHub account [dileepadev](https://github.com/dileepadev) and domain [dileepa.dev](https://dileepa.dev).

## 💬 Contact

If you want to contact me, leave a message via email.

- Email - <contact@dileepa.dev>

## 📜 License

This project is licensed under the MIT License.  
See the license file for more details [LICENSE](./LICENSE)
