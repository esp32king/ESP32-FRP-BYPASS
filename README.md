<img src="https://komarev.com/ghpvc/?username=esp32king4&label=Profile%20views&color=0e75b6&style=flat" alt="visitor counter" />

# 📱BYPASS-FRP-WITH-ESP32-CAPTIVE-PORTAL


A lightweight **ESP32 Wi-Fi Captive Portal** project designed for Android activity/intent testing in an authorized lab environment.

The ESP32 creates its own Wi-Fi Access Point and redirects connected clients to a local web interface. After authentication, the interface provides categorized Android activity/intent shortcuts for testing and research.

> ⚠️ **Disclaimer:** This project is intended for educational, development, and authorized testing purposes only. Do not use it to bypass security controls, device protection, or accounts on devices you do not own or have permission to test.

---
<img src="https://raw.githubusercontent.com/esp32king/ESP32-FRP-BYPASS/refs/heads/main/Files/Ss.jpg"></img>

<img src="https://raw.githubusercontent.com/esp32king/ESP32-FRP-BYPASS/refs/heads/main/Files/Ssss.jpg"></img>


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

## ⚙️ Configuration

You can change the Wi-Fi name and login credentials near the top of the sketch:

```cpp
const char* ssid = "GodxShadow";

const char* LOGIN_USER = "linuxndroid";
const char* LOGIN_PASS = "krishna";
```

For your own deployment, **change the default credentials** before sharing or using the project.

---
### 1. Select the COM port

Connect your ESP32 using USB and select the correct port.

### Code Flash
Flash Here 👉 <a href="https://esptool.spacehuhn.com">Esptool.spacehuhn.com</a>

### 2nd Step
<a href="https://github.com/esp32king/ESP32-FRP-BYPASS/releases/download/bypass-frp-through-esp32/bootloader.bin">bootloader.bin</a> → 0x1000

<a href="https://github.com/esp32king/ESP32-FRP-BYPASS/releases/download/bypass-frp-through-esp32/partitions.bin">partitions.bin</a> → 0x8000

<a href="https://github.com/esp32king/ESP32-FRP-BYPASS/releases/download/bypass-frp-through-esp32/FRP-BYPASS.bin">Esp32-FRP-BYPASS.bin</a> → 0x10000

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

Special thanks to HIRU ❤️

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
