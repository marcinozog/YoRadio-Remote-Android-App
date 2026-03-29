# 📻 YoRadio Remote

YoRadio Remote is an Android application designed to control and interact with the YoRadio device over the network.

It provides a simple and responsive interface for managing radio playback, alarms, and text-to-speech features, acting as a companion app for the YoRadio system.

# ✨ Features
📡 Remote control of YoRadio device
Connect via WebSocket
Real-time synchronization with device state
🎵 Station management
Browse available stations
Select and switch stations instantly
Highlight currently playing station
🔊 Volume & audio control
Adjust volume remotely
Equalizer controls (if enabled on device)
⏰ Alarm management
Create and schedule alarms
Exact alarm triggering support
Persistent after reboot
🗣️ Text-to-Speech (TTS) integration
Generate spoken messages
Language selection support
WAV generation and playback synchronization
🔄 Connection handling
Automatic reconnect
Connection state monitoring
📱 Screenshots
<!-- Add your screenshots here -->
Main Screen

Station List

Alarm Configuration

TTS Settings

# 🧠 Architecture Overview

The application is built using modern Android technologies:

Kotlin + Jetpack Compose – UI layer
WebSocket communication – real-time control
Foreground services – alarm & TTS handling
Modular structure – separation of UI, logic, and services

Core components:

AlarmsScreen – alarm scheduling and management
TTSService – handles speech synthesis and playback
WebSocket client – communication with YoRadio device
UI state synchronization with backend
⚙️ Requirements
Android device (API level depending on your config)
YoRadio device running and accessible via network
Proper permissions:
INTERNET
SCHEDULE_EXACT_ALARM
RECEIVE_BOOT_COMPLETED
Foreground service permissions (for TTS/alarm)
🚀 Getting Started

Clone the repository:

git clone https://github.com/your-repo/yoradio-remote.git
Open in Android Studio
Configure connection to your YoRadio device (IP / host)
Build and run on your device
⚠️ Notes
Some TTS languages may not be available depending on the device
TextToSpeech.availableLanguages may return unsupported entries
Alarm behavior depends on system restrictions (especially on newer Android versions)
📌 Future Improvements
Better TTS language filtering and validation
Improved UI feedback for connection states
More advanced station management
Background stability improvements for services
📄 License

(Add your license here)

# 🤝 Contributing

Contributions, ideas, and bug reports are welcome!
