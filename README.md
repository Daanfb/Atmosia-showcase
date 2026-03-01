# Atmosia: Relaxing Sounds

A modern, user-friendly, native Android application built in **Kotlin** with **Jetpack Compose**. It allows users to combine over 50 ambient sounds into custom relaxing mixes, offering an immersive user experience designed to reduce stress, beat insomnia, and boost productivity.

<img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Coming soon on Google Play Store" width="240"/>

### ⚠️ Coming soon to the Google Play Store
*(The app is currently under review for publication)*

## 📱 Features

* **Extensive Sound Library**: Access over 50 high-fidelity ambient sounds neatly categorized into Water, Animals, Transport, and Indoor environments.
* **Custom Audio Mixer**: Combine multiple sounds simultaneously and adjust the volume of each track independently to create your perfect atmosphere.
* **Ready-made Mixes**: Enjoy expertly crafted, predefined atmospheres designed for specific moments: Sleep, Focus, Nature, and Travel.
* **Smart Sleep Timer**: Fall asleep without worries by setting a custom timer to gently stop the audio playback and save battery life.
* **Background Playback**: Keep listening to your relaxing mixes even when the screen is off or while using other apps.
* **Media Notification Controls**: Control your active mixes (pause, resume, or stop) directly from the system's media session notification.
* **TalkBack Support**: Fully optimized for accessibility to ensure a great experience for all users.
* **Multiple Languages Supported**: The application is fully localized and available in English, Spanish, Portuguese, Italian, and French.

## 🛠️ Tech Stack

| Component                 | Technology                             |
|:--------------------------| :------------------------------------- |
| **UI**                    | Jetpack Compose                        |
| **Architecture**          | MVVM & Clean Architecture              |
| **Dependency Injection**  | Koin                                   |
| **Navigation**            | Compose Navigation                     |
| **Local Database**        | Room                                   |
| **Audio**                 | ExoPlayer (Media3)                     |
| **Foreground Service**    | Media Session                          |
| **Analytics**             | Firebase Analytics                     |
| **Crash Reporting**       | Firebase Crashlytics                   |
| **Wave Animation**        | Rive                                   |

## 📸 Screenshots

| **Home** | **Audio Mixer - No Sounds** | **Sounds Selector** |
|:---:|:---:|:---:|
| <img src="screenshots/home_screen.png" alt="Home screen" width="200"/> | <img src="screenshots/custom_mix_no_sounds.png" alt="Audio mixer - no sounds" width="200"/> | <img src="screenshots/sounds_selector.png" alt="Sounds selector" width="200"/> |
| **Chorometer - No Session Started**| **Timer - No timer set** | **Set time** |
| <img src="screenshots/chrono_session_no_started.png" alt="chronometer session not started" width="200"/> | <img src="screenshots/timer_session_no_started.png" alt="Timer session with no time set" width="200"/> | <img src="screenshots/timer_screen.png" alt="Set time" width="200"/> |
| **Timer - Session started**| **Manage tracks** | **Notification** |
| <img src="screenshots/active_session.png" alt="active session" width="200"/> | <img src="screenshots/manage_tracks.png" alt="Manage tracks" width="200"/> | <img src="screenshots/notification.png" alt="Session notification" width="200"/> |
| **Session paused**| |  |
| <img src="screenshots/paused_session.png" alt="session paused" width="200"/> |  |  |
