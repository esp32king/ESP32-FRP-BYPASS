# ESP32-RFP-BYPASS-WITH-CAPTIVE-PORTAL
# 📱 ESP32 Android Activity Launcher — Captive Portal

A lightweight **ESP32 Wi-Fi Captive Portal** project designed for Android activity/intent testing in an authorized lab environment.

The ESP32 creates its own Wi-Fi Access Point and redirects connected clients to a local web interface. After authentication, the interface provides categorized Android activity/intent shortcuts for testing and research.

> ⚠️ **Disclaimer:** This project is intended for educational, development, and authorized testing purposes only. Do not use it to bypass security controls, device protection, or accounts on devices you do not own or have permission to test.

---

## ✨ Features

* 📡 ESP32 Wi-Fi Access Point
* 🌐 Captive portal using `DNSServer`
* 🔐 Local username/password authentication
* 📱 Android intent/activity launcher interface
* 🗂️ Device/category-based activity sections
* ⚡ Lightweight HTML/CSS interface
* 🔄 Automatic captive-portal redirection
* 📶 Works without an external internet connection
* 🛠️ Designed for ESP32 + Arduino IDE

---

## 🔧 Hardware

### Required

* ESP32 development board
* USB cable
* Computer with Arduino IDE

No additional hardware is required.

---

## 📚 Libraries

The project uses the following Arduino libraries:

```text
WiFi.h
WebServer.h
DNSServer.h
```

These are available with the ESP32 Arduino core.

---

## ⚙️ Configuration

You can change the Wi-Fi name and login credentials near the top of the sketch:

```cpp
const char* ssid = "Free WiFi";

const char* LOGIN_USER = "linuxndroid";
const char* LOGIN_PASS = "krishna";
```

For your own deployment, **change the default credentials** before sharing or using the project.

---

## 🚀 Installation

### 1. Install Arduino IDE

Install Arduino IDE and add ESP32 board support.

### 2. Open the sketch

Open the `.ino` file in Arduino IDE.

### 3. Select your board

For example:

```text
Tools → Board → ESP32 Arduino → ESP32 Dev Module
```

### 4. Select the COM port

Connect your ESP32 using USB and select the correct port.

### 5. Upload

Click:

```text
Upload
```

### 6. Open Serial Monitor

Set the baud rate to:

```text
115200
```

The ESP32 will display its Access Point information.

---

## 📡 Connecting

After uploading:

1. Power on the ESP32.
2. Search for the configured Wi-Fi network.
3. Connect to the ESP32 Access Point.
4. Open the captive portal.
5. Enter the configured credentials.
6. The Android testing interface will be displayed.

Default local address:

```text
http://192.168.4.1
```

---

## 📂 Categories

The interface contains Android activity/intent examples organized into sections such as:

* General Android
* Device Settings
* Lock Screen & Security
* Google Apps
* 3rd Party Apps
* Samsung
* Motorola
* Xiaomi
* OnePlus
* OPPO
* Infinix
* Huawei
* LG
* Sony
* HTC
* Nokia
* Asus
* Realme
* Google Pixel

> Availability of individual intents depends on the Android version, manufacturer, installed applications, and device security configuration.

---

## 🧪 Intended Use

This project can be useful for:

* Android intent research
* Captive portal development
* ESP32 web-server experiments
* Android application testing
* Learning about custom URI schemes
* Authorized mobile-device lab testing

---

## ⚠️ Important Limitations

Android does **not** guarantee that every intent or activity can be launched.

Some activities may:

* Not exist on a particular device
* Require special permissions
* Be protected by Android
* Be unavailable on newer Android versions
* Require a specific manufacturer package
* Be blocked by the browser or operating system

Therefore, an intent working on one phone does not necessarily mean it will work on another.

---

## 🔐 Security

This project uses simple local authentication:

```text
Username: linuxndroid
Password: krishna
```

These credentials are stored directly in the ESP32 firmware.

**Do not use these default credentials for a real deployment.**

Also note that the login page uses HTTP rather than HTTPS, so credentials should not be considered securely encrypted during transmission.

---

## 👨‍💻 Credits

**Created by Krishna Chauhan — UP61**

Made with ❤️ by **@linuxndroid**

GitHub:

**https://instagram.com/krishna_upx61**

YouTube:

**https://youtube.com/@linuxndroid**

---

## ❤️ Support & Credits

If you use or modify this project, please keep the original credits.

You are welcome to:

* Fork the project
* Modify the code
* Improve the UI
* Add new Android intent examples
* Submit improvements

Please give proper credit to the original author.

---

## 📜 License

This project is provided for educational and authorized testing purposes.

Users are responsible for ensuring that their use of the project complies with applicable laws, device-owner permissions, and platform security policies.

---

### ⭐ If this project helped you

Consider giving the repository a **Star ⭐** and following the project for future ESP32 experiments.

**Created by Krishna Chauhan UP61**
**Made with ❤️ @linuxndroid**
