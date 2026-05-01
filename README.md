# Atmosia: Relaxing Sounds

A modern, user-friendly, native Android application built in **Kotlin** with **Jetpack Compose**. It allows users to combine over 80 ambient sounds into custom relaxing mixes, offering an immersive user experience designed to reduce stress, beat insomnia, and boost productivity.

<a href="https://play.google.com/store/apps/details?id=com.danfb.atmosia">
  <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" width="240"/>
</a>

## 📱 Features

* **Extensive Sound Library**: Access over 80 high-fidelity ambient sounds neatly categorized into Water, Nature, Animals, Transport, and Indoor environments.
* **Secure User Authentication**: Sign up and log in seamlessly using your Email or Google Account.
* **Account Management**: Includes essential user flows such as Password Reset and the ability to permanently delete your account and data, ensuring full GDPR/Google Play compliance.
* **Custom Audio Mixer**: Combine multiple sounds simultaneously and adjust the volume of each track independently to create your perfect atmosphere.
* **Ready-made Mixes**: Enjoy expertly crafted, predefined atmospheres designed for specific moments: Sleep, Focus, Nature, and Travel.
* **Cloud Sync & Storage**: Your custom sound mixes are automatically saved in Firestore, allowing you to access your personal library from any device, anytime.
* **Smart Sleep Timer**: Fall asleep without worries by setting a custom timer to gently stop the audio playback and save battery life.
* **Background Playback**: Keep listening to your relaxing mixes even when the screen is off or while using other apps.
* **Media Notification Controls**: Control your active mixes (pause, resume, or stop) directly from the system's media session notification.
* **Open app reminder Notification**: Notification that trigger after a period of inactivity to ensure your app stays part of the user's routine.
* **In-app Review**: Support in-app review to increase the change the user leave a review.
* **In-app Update**: Support in-app update to provide a seamless way for users to stay up-to-date.
* **In-app Subscription**: Subscription management integrated via RevenueCat to handle premium tiers.
* **TalkBack Support**: Fully optimized for accessibility to ensure a great experience for all users.
* **Multiple Languages Supported**: The application is fully localized and available in English, Spanish, Portuguese, Italian, and French.

## 🛠️ Tech Stack

| Component                 | Technology                             |
|:--------------------------| :------------------------------------- |
| **UI**                    | Jetpack Compose                        |
| **Architecture**          | MVVM & Clean Architecture              |
| **Dependency Injection**  | Koin                                   |
| **Navigation**            | Compose Navigation                     |
| **Authentication**        | Firebase Auth (Email & Google)         |
| **Local Database**        | Room                                   |
| **Cloud Database**        | Firebase Firestore                     |
| **Audio**                 | ExoPlayer (Media3)                     |
| **Foreground Service**    | Media Session                          |
| **Reminder Notification** |	WorkManager                            |
| **Ads**                   | Google AdMob                           |
| **Subscription**          | RevenueCat                             |
| **Analytics**             | Firebase Analytics                     |
| **Crash Reporting**       | Firebase Crashlytics                   |
| **Wave Animation**        | Rive                                   |

## 📸 Screenshots

| **Explore** | **Login to access** | **Sign in** | **No mixes created** |
|:---:|:---:|:---:|:---:|
| <img src="screenshots/explore_screen.png" alt="Explore screen" width="200"/> | <img src="screenshots/login_to_access_mix.png" alt="Login to access to your mixes" width="200"/> | <img src="screenshots/sign_in.png" alt="Sign in" width="200"/> | <img src="screenshots/no_mixes.png" alt="No mixes created" width="200"/> |
| **Audio Mixer - No Sounds** | **Sounds Selector** | **Chorometer - No Session Started** | **Save mix** |
| <img src="screenshots/custom_mix_no_sounds.png" alt="Audio mixer - no sounds" width="200"/> | <img src="screenshots/sounds_selector.png" alt="Sounds selector" width="200"/> | <img src="screenshots/chrono_session_no_started.png" alt="Chronometer session not started" width="200"/> | <img src="screenshots/save_mix.png" alt="Save mix dialog" width="200"/> |
| **Timer - No timer set** | **Set time** | **Timer - Session started** | **Manage tracks** |
| <img src="screenshots/timer_session_no_started.png" alt="Timer session with no time set" width="200"/> | <img src="screenshots/timer_screen.png" alt="Set time" width="200"/> | <img src="screenshots/active_session.png" alt="active session" width="200"/> | <img src="screenshots/manage_tracks.png" alt="Manage tracks" width="200"/> |
| **Notification** | **Session paused** | **My mixes** | **My mix - Options** |
| <img src="screenshots/notification.png" alt="Session notification" width="200"/> | <img src="screenshots/paused_session.png" alt="session paused" width="200"/> | <img src="screenshots/my_mixes.png" alt="My mixes screen" width="200"/> | <img src="screenshots/my_mix_options.png" alt="My mix - Options bottom sheet" width="200"/> |
| **In-app Update** |  |  |  |
| <img src="screenshots/in-app_update.png" alt="In-app update" width="200"/> |  |  |  |

## 📞 Contact

**Daniel Frías** - [danielfb2312@gmail.com](mailto:danielfb2312@gmail.com) - [LinkedIn Profile](https://www.linkedin.com/in/daniel-frias-balbuena/)
