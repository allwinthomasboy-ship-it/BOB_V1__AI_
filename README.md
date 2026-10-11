🤖 BOB AI V1 — Mini Voice Assistant Robot

By ALLWIN TECH

BUILD. CREATE. INNOVATE.

BOB AI V1 is a mini robot assistant project built using an ESP32-S3 Mini. The goal is to develop a compact, button-free voice assistant that can listen for supported spoken commands, display animated expressions on an OLED screen, and respond with predefined answers.

This project is being developed step by step, starting with the OLED display and progressing toward offline voice recognition and audio responses.

---

🎯 Project Goals

- 🤖 Develop a mini robot assistant.
- 👀 Display animated eyes and expressions on an OLED screen.
- 🎤 Use an INMP441 microphone for voice input.
- 🔊 Use a MAX98357A amplifier and speaker for audio output.
- 🧠 Recognize supported voice commands without an internet connection.
- 💬 Respond to predefined questions using stored answers.
- 🔘 Work without a physical wake button.
- 🚀 Explore more advanced AI features in future versions.

Note: Offline voice recognition and speaker responses are planned features. They require additional firmware and speech-processing integration and are not provided by the OLED demonstration code alone.

---

🛠️ Hardware Components

No.| Component| Purpose
1| ESP32-S3 Mini| Main controller
2| SSD1306 0.96-inch OLED| Displays animated eyes and status
3| INMP441 I2S Microphone| Captures voice input
4| MAX98357A I2S Amplifier| Drives the speaker
5| Mini Speaker| Audio output
6| Connecting Wires| Hardware connections
7| USB Cable| Programming and power

---

🔌 Pin Connections

1. OLED Display — SSD1306 I2C

OLED Pin| ESP32-S3 Mini
SDA| GPIO 5
SCL| GPIO 6
VCC| 3.3V
GND| GND

2. INMP441 Microphone

Microphone Pin| ESP32-S3 Mini
SCK| GPIO 8
WS| GPIO 10
SD| GPIO 11
VDD| 3.3V
GND| GND
L/R| GND for left channel, if required by the module

3. MAX98357A Audio Amplifier

Amplifier Pin| ESP32-S3 Mini
BCLK| GPIO 4
LRC| GPIO 2
DIN| GPIO 1
VIN| Compatible power supply
GND| GND

Connect the speaker to the amplifier's speaker output terminals.

Important: Confirm your modules' voltage requirements and ensure all components share a common ground. Never connect a speaker output terminal directly to an ESP32 GPIO.

---

💻 Software Requirements

- Arduino IDE
- ESP32 board support package
- U8g2 graphics library
- USB data cable

Additional software and speech-recognition models may be required to implement offline voice recognition.

---

⚙️ Current Development Status

- [x] ESP32-S3 Mini selected as the controller
- [x] Hardware pin connections planned
- [x] OLED display development started
- [ ] Complete animated OLED interface
- [ ] INMP441 microphone integration
- [ ] Offline voice-command recognition
- [ ] Predefined question-and-answer system
- [ ] MAX98357A audio playback
- [ ] Full button-free assistant integration

---

🧠 How BOB AI Is Intended to Work

1. BOB starts when powered on.
2. Animated eyes appear on the OLED display.
3. The microphone captures the user's voice.
4. Offline speech-processing software identifies supported commands.
5. BOB searches its predefined question-and-answer database.
6. The OLED displays a response or expression.
7. The speaker plays a prerecorded or synthesized answer.

The complete process will work offline once the required recognition and audio features have been implemented.

---

🚀 Future Improvements

- More predefined questions and answers
- Cute expressions and emotion animations
- Tamil, English, and Hindi support
- Time and weather features
- Music playback
- Smart-home control
- Advanced AI integration in future versions

Some future features may require an internet connection or additional hardware and software.

---

👨‍💻 Developer

Project: BOB AI V1
Brand: ALLWIN TECH
Organization: ALLWIN INNOVATION LAB
Tagline: BUILD. CREATE. INNOVATE.

---

📜 License

This project is currently intended for learning, experimentation, and educational development. Add a formal open-source license if you decide how others may use, modify, and distribute your code.

---

⭐ If you are interested in robotics, ESP32 projects, and voice assistants, follow the development of BOB AI V1!

BOB AI V1 — A Small Robot with Big Dreams. 🤖
