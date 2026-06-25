# Atmosia: Relaxing Sounds

A modern, user-friendly, native Android application built in **Kotlin** with **Jetpack Compose**. It allows users to combine over 90 ambient sounds into custom relaxing mixes, offering an immersive user experience designed to reduce stress, beat insomnia, and boost productivity.

Visit the [Atmosia Landing Page](https://atmosia-ae339.web.app/) to explore all features.

<a href="https://play.google.com/store/apps/details?id=com.danfb.atmosia">
  <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" width="240"/>
</a>

## 📱 Features

* **Extensive Sound Library**: Access over 100 high-fidelity ambient sounds neatly categorized into Water, Nature, Animals, Transport, and Indoor environments.
* **Secure User Authentication**: Sign up and log in seamlessly using your Email or Google Account.
* **Account Management**: Includes essential user flows such as Password Reset and the ability to permanently delete your account and data, ensuring full GDPR/Google Play compliance.
* **Custom Audio Mixer**: Combine multiple sounds simultaneously and adjust the volume of each track independently to create your perfect atmosphere.
* **Ready-made Mixes**: Enjoy expertly crafted, predefined atmospheres designed for specific moments: Sleep, Focus, Nature, and Travel.
* **Cloud Sync & Storage**: Your custom sound mixes are automatically saved in Firestore, allowing you to access your personal library from any device, anytime.
* **Time Management**: Choose between timer, stopwatch and pomodoro timer.
* **Background Playback**: Keep listening to your relaxing mixes even when the screen is off or while using other apps.
* **Media Notification Controls**: Control your active mixes (pause, resume, or stop) directly from the system's media session notification.
* **Open app reminder Notification**: Notification that trigger after a period of inactivity to ensure your app stays part of the user's routine.
* **In-app Review**: Support in-app review to increase the change the user leave a review.
* **In-app Update**: Support in-app update to provide a seamless way for users to stay up-to-date.
* **In-app Subscription**: Subscription management integrated via RevenueCat to handle premium tiers.
* **TalkBack Support**: Fully optimized for accessibility to ensure a great experience for all users.
* **Multiple Languages Supported**: The application is fully localized and available in English, Spanish, Portuguese, Italian, French, German, Dutch, Romanian, Indonesian, Turkish, Hindi and Arabic (support RTL language).

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
| **Ads**                   | Google AdMob (Native & Interstitial)   |
| **Subscription**          | RevenueCat                             |
| **Analytics**             | Firebase Analytics                     |
| **Crash Reporting**       | Firebase Crashlytics                   |
| **Wave Animation**        | Rive                                   |

## 📸 Screenshots

| **Explore** | **Login to access** | **Sign in** | **No mixes created** |
|:---:|:---:|:---:|:---:|
| <img src="screenshots/explore_screen.png" alt="Explore screen" width="200"/> | <img src="screenshots/login_to_access_mix.png" alt="Login to access to your mixes" width="200"/> | <img src="screenshots/sign_in.png" alt="Sign in" width="200"/> | <img src="screenshots/no_mixes.png" alt="No mixes created" width="200"/> |
| **Audio Mixer - No Sounds** | **Sounds Selector** | **Modes** | **Save mix** | 
| <img src="screenshots/empty_mixer.png" alt="Audio mixer - no sounds" width="200"/> | <img src="screenshots/sounds_selector.png" alt="Sounds selector" width="200"/> | <img src="screenshots/modes.png" alt="Time management modes" width="200"/> | <img src="screenshots/create_mix.png" alt="Save mix dialog" width="200"/> |
| **Chorometer - No session started** | **Timer - No timer set** | **Timer - Config** | **Timer - Session started** |
| <img src="screenshots/chrono_not_started.png" alt="Chronometer session not started" width="200"/> | <img src="screenshots/timer_not_set.png" alt="Timer session with no time set" width="200"/> | <img src="screenshots/timer_config.png" alt="Timer config" width="200"/> | <img src="screenshots/session_started.png" alt="Timer - Session started" width="200"/> |
| **Pomodoro - Config**| **Pomodoro - No session started**| **Pomodoro - Session started** | **Manage tracks** | 
| <img src="screenshots/pomodoro_config.png" alt="Pomodoro config" width="200"/> | <img src="screenshots/pomodoro_not_started.png" alt="Pomodoro session not started" width="200"/> | <img src="screenshots/pomodoro_session_started.png" alt="Pomodoro session started break phase" width="200"/> |<img src="screenshots/manage_sounds.png" alt="Manage tracks" width="200"/> |
| **Notification** | **My mixes** | **My mix - Options** | **In-app Update** |
| <img src="screenshots/notification.png" alt="Session notification" width="200"/> | <img src="screenshots/my_mixes.png" alt="My mixes screen" width="200"/> | <img src="screenshots/my_mix_options.png" alt="My mix - Options bottom sheet" width="200"/> | <img src="screenshots/in-app_update.png" alt="In-app update" width="200"/> |

## 📞 Contact

**Daniel Frías** - [danielfb2312@gmail.com](mailto:danielfb2312@gmail.com) - [LinkedIn Profile](https://www.linkedin.com/in/daniel-frias-balbuena/)
