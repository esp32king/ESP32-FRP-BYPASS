
<a href="https://vnrom.net/bypass/">vnrom</a>
<img src="https://komarev.com/ghpvc/?username=esp32king4&label=Profile%20views&color=0e75b6&style=flat" alt="visitor counter" />

# 📱BYPASS-FRP-WITH-ESP32-CAPTIVE-PORTAL


A lightweight **ESP32 Wi-Fi Captive Portal** project designed for Android activity/intent testing in an authorized lab environment.

The ESP32 creates its own Wi-Fi Access Point and redirects connected clients to a local web interface. After authentication, the interface provides categorized Android activity/intent shortcuts for testing and research.

> ⚠️ **Disclaimer:** This project is intended for educational, development, and authorized testing purposes only. Do not use it to bypass security controls, device protection, or accounts on devices you do not own or have permission to test.

---
<img src="https://raw.githubusercontent.com/esp32king/ESP32-FRP-BYPASS/refs/heads/main/Files/Ss.jpg"></img>

<img src="https://raw.githubusercontent.com/esp32king/ESP32-FRP-BYPASS/refs/heads/main/Files/Ssss.jpg"></img>

 📹 Video Link
https://youtube.com/shorts/mAdyU4vBJqI?si=vFh3LIRxTioDgS00

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




*GitHub: https://github.com/esp32king*

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


<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Primary Meta Tags -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>FRP Bypass Pro 2025 | Android FRP Unlock Tool - Samsung, Xiaomi, Oppo, Vivo</title>
    <meta name="description" content="Professional FRP Bypass Tool 2025 - Unlock Android FRP lock on Samsung, Xiaomi, Oppo, Vivo, Realme. 95+ verified tools for Android 5-16. Free FRP bypass methods, Google account bypass, factory reset protection removal.">
    <meta name="keywords" content="FRP bypass, FRP unlock, Android FRP bypass, Samsung FRP bypass, Google account bypass, FRP lock removal, factory reset protection bypass, FRP bypass tool 2025, unlock FRP Android, remove FRP lock, bypass Google verification, Android unlock tool, FRP bypass APK, Samsung FRP unlock, Xiaomi FRP bypass, Oppo FRP bypass, Vivo FRP bypass, Realme FRP bypass, FRP bypass without PC, FRP bypass online, Android 15 FRP bypass, Android 14 FRP bypass, unlock Google account, remove factory reset protection, FRP bypass methods, professional FRP tool, free FRP bypass">
    <meta name="author" content="FRP Bypass Pro">
    <meta name="robots" content="index, follow, max-image-preview:large, max-snippet:-1, max-video-preview:-1">
    <link rel="canonical" href="https://itechmobile.site/">
    
    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://itechmobile.site/">
    <meta property="og:title" content="FRP Bypass Pro 2025 | Professional Android FRP Unlock Tool">
    <meta property="og:description" content="Unlock Android FRP lock with 95+ verified tools. Works on Samsung, Xiaomi, Oppo, Vivo - Android 5-16. Free professional FRP bypass methods.">
    <meta property="og:image" content="https://itechmobile.site/og-image.jpg">
    <meta property="og:site_name" content="FRP Bypass Pro">
    <meta property="og:locale" content="en_US">
    
    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image">
    <meta property="twitter:url" content="https://itechmobile.site/">
    <meta property="twitter:title" content="FRP Bypass Pro 2025 | Android FRP Unlock Tool">
    <meta property="twitter:description" content="Professional FRP bypass tool with 95+ verified methods for all Android devices. Free and updated for 2025.">
    <meta property="twitter:image" content="https://itechmobile.site/twitter-image.jpg">
    
    <!-- Additional SEO Meta Tags -->
    <meta name="theme-color" content="#00ffaa">
    <meta name="application-name" content="FRP Bypass Pro">
    <meta name="apple-mobile-web-app-title" content="FRP Bypass Pro">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <meta name="mobile-web-app-capable" content="yes">
    <meta name="format-detection" content="telephone=no">
    
    <!-- Geo Tags -->
    <meta name="geo.region" content="US">
    <meta name="geo.placename" content="United States">
    
    <!-- Language Alternates -->
    <link rel="alternate" hreflang="en" href="https://itechmobile.site/">
    <link rel="alternate" hreflang="es" href="https://itechmobile.site/es/">
    <link rel="alternate" hreflang="fr" href="https://itechmobile.site/fr/">
    <link rel="alternate" hreflang="de" href="https://itechmobile.site/de/">
    <link rel="alternate" hreflang="pt" href="https://itechmobile.site/pt/">
    <link rel="alternate" hreflang="ar" href="https://itechmobile.site/ar/">
    <link rel="alternate" hreflang="hi" href="https://itechmobile.site/hi/">
    <link rel="alternate" hreflang="x-default" href="https://itechmobile.site/">
    
    <!-- Favicons -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect fill='%2300ffaa' width='100' height='100'/%3E%3Ctext fill='%23000' font-size='60' x='50%25' y='65%25' text-anchor='middle' font-weight='bold'%3E🔓%3C/text%3E%3C/svg%3E">
    <link rel="apple-touch-icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 180 180'%3E%3Crect fill='%2300ffaa' width='180' height='180'/%3E%3Ctext fill='%23000' font-size='80' x='50%25' y='55%25' text-anchor='middle' dominant-baseline='middle' font-weight='bold'%3EFRP%3C/text%3E%3C/svg%3E">
    
    <!-- PWA Manifest -->
    <link rel="manifest" href="data:application/manifest+json,{%22name%22:%22FRP%20Bypass%20Pro%202025%22,%22short_name%22:%22FRP%20Pro%22,%22start_url%22:%22.%22,%22display%22:%22standalone%22,%22background_color%22:%22%230f0f1e%22,%22theme_color%22:%22%2300ffaa%22,%22description%22:%22Professional%20Android%20FRP%20Bypass%20Tool%22,%22icons%22:[{%22src%22:%22data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 192 192'%3E%3Crect fill='%2300ffaa' width='192' height='192'/%3E%3Ctext fill='%23000' font-size='80' x='50%25' y='55%25' text-anchor='middle' dominant-baseline='middle' font-weight='bold'%3EFRP%3C/text%3E%3C/svg%3E%22,%22sizes%22:%22192x192%22,%22type%22:%22image/svg+xml%22}]}">
    
    <!-- Google Analytics 4 -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
    <script>
      window.dataLayer = window.dataLayer || [];
      function gtag(){dataLayer.push(arguments);}
      gtag('js', new Date());
      gtag('config', 'G-XXXXXXXXXX', {
        'page_title': 'FRP Bypass Pro',
        'page_location': window.location.href,
        'send_page_view': true
      });
    </script>
    
    <!-- Google Tag Manager -->
    <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
    new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
    j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
    'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
    })(window,document,'script','dataLayer','GTM-XXXXXXX');</script>
    
    <!-- Schema.org Structured Data -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "SoftwareApplication",
      "name": "FRP Bypass Pro",
      "applicationCategory": "UtilitiesApplication",
      "operatingSystem": "Android 5.0 and above",
      "offers": {
        "@type": "Offer",
        "price": "0",
        "priceCurrency": "USD"
      },
      "aggregateRating": {
        "@type": "AggregateRating",
        "ratingValue": "4.8",
        "ratingCount": "15420",
        "bestRating": "5",
        "worstRating": "1"
      },
      "description": "Professional FRP Bypass Tool for Android devices with 95+ verified methods",
      "softwareVersion": "2.0.0",
      "datePublished": "2025-01-01",
      "author": {
        "@type": "Organization",
        "name": "FRP Bypass Pro"
      }
    }
    </script>
    
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "FAQPage",
      "mainEntity": [{
        "@type": "Question",
        "name": "What is FRP Bypass?",
        "acceptedAnswer": {
          "@type": "Answer",
          "text": "FRP (Factory Reset Protection) bypass is a method to access Android devices that are locked after a factory reset. This tool provides authorized device owners with quick access to system functions."
        }
      },{
        "@type": "Question",
        "name": "Which Android devices are supported?",
        "acceptedAnswer": {
          "@type": "Answer",
          "text": "FRP Bypass Pro supports all major Android brands including Samsung, Xiaomi, Oppo, Vivo, Realme, and more, running Android 5.0 through Android 16."
        }
      },{
        "@type": "Question",
        "name": "Is FRP Bypass Pro free to use?",
        "acceptedAnswer": {
          "@type": "Answer",
          "text": "Yes, FRP Bypass Pro is completely free and provides 95+ verified tools for authorized device access."
        }
      }]
    }
    </script>
    
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@700;800;900&family=Inter:wght@400;500;600;700;800&display=swap');
        
        :root {
            --primary: #00ffaa;
            --primary-dark: #00cc88;
            --primary-glow: rgba(0, 255, 170, 0.15);
            --secondary: #667eea;
            --accent: #f093fb;
            --bg: #0d0d1c;
            --bg-gradient: linear-gradient(135deg, #0a0a1a 0%, #1a1a2e 100%);
            --card: rgba(25, 30, 55, 0.95);
            --border: rgba(0, 255, 170, 0.2);
            --warning: rgba(255, 51, 102, 0.25);
            --warning-border: #ff3366;
            --success: rgba(0, 255, 170, 0.2);
            --success-border: #00ffaa;
        }
        
        * { 
            margin: 0; 
            padding: 0; 
            box-sizing: border-box; 
            -webkit-tap-highlight-color: transparent; 
        }
        
        body { 
            background: var(--bg-gradient);
            color: #eee; 
            font-family: 'Inter', sans-serif;
            min-height: 100dvh;
            padding: env(safe-area-inset-top) env(safe-area-inset-right) calc(env(safe-area-inset-bottom) + 100px) env(safe-area-inset-left);
            overflow-x: hidden;
            position: relative;
        }
        
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle at 20% 50%, rgba(0, 255, 170, 0.1) 0%, transparent 50%),
                        radial-gradient(circle at 80% 80%, rgba(102, 126, 234, 0.1) 0%, transparent 50%);
            pointer-events: none;
            z-index: 0;
        }
        
        .container {
            position: relative;
            z-index: 1;
        }
        
        header { 
            text-align: center; 
            padding: min(8vh, 50px) 5vw min(4vh, 30px);
            position: relative;
        }
        
        .logo-container {
            display: inline-block;
            position: relative;
            margin-bottom: 15px;
        }
        
        .logo {
            width: clamp(70px, 15vw, 120px);
            height: clamp(70px, 15vw, 120px);
            background: linear-gradient(135deg, var(--primary), var(--primary-dark));
            border-radius: 24px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: clamp(2rem, 8vw, 3.5rem);
            font-weight: 900;
            box-shadow: 0 20px 60px rgba(0, 255, 170, 0.4),
                        0 0 0 1px rgba(0, 255, 170, 0.2);
            animation: pulse 3s ease-in-out infinite;
        }
        
        @keyframes pulse {
            0%, 100% { transform: scale(1); box-shadow: 0 20px 60px rgba(0, 255, 170, 0.4); }
            50% { transform: scale(1.05); box-shadow: 0 25px 80px rgba(0, 255, 170, 0.6); }
        }
        
        h1 { 
            font-family: 'Orbitron', sans-serif; 
            font-size: clamp(2.2rem, 9vw, 4rem); 
            color: var(--primary); 
            text-shadow: 0 0 30px var(--primary), 0 0 60px rgba(0, 255, 170, 0.3);
            margin: 15px 0 10px;
            line-height: 1.1;
            letter-spacing: 0.02em;
            font-weight: 900;
        }
        
        .tagline { 
            font-size: clamp(1rem, 3.8vw, 1.3rem); 
            margin: 10px 0 6px; 
            opacity: 0.9;
            font-weight: 500;
            background: linear-gradient(90deg, #00ffaa, #667eea);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .stats-bar {
            display: flex;
            justify-content: center;
            gap: clamp(15px, 4vw, 30px);
            margin: 20px 0;
            flex-wrap: wrap;
        }
        
        .stat {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 12px 20px;
            background: rgba(0, 255, 170, 0.1);
            border: 1px solid rgba(0, 255, 170, 0.3);
            border-radius: 12px;
            min-width: 100px;
        }
        
        .stat-value {
            font-size: clamp(1.5rem, 5vw, 2rem);
            font-weight: 800;
            color: var(--primary);
            line-height: 1;
        }
        
        .stat-label {
            font-size: clamp(0.75rem, 2.5vw, 0.9rem);
            opacity: 0.8;
            margin-top: 4px;
        }
        
        .updated { 
            font-size: clamp(0.9rem, 3.2vw, 1.1rem); 
            color: #00ff88; 
            font-weight: 700;
            letter-spacing: 0.01em;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 8px 16px;
            background: rgba(0, 255, 136, 0.1);
            border-radius: 20px;
            margin-top: 10px;
        }
        
        .notice { 
            margin: 15px 5vw 20px; 
            padding: 20px 24px; 
            background: var(--warning);
            border: 2px solid var(--warning-border); 
            border-radius: 20px; 
            font-size: clamp(0.9rem, 3.5vw, 1.05rem); 
            text-align: center;
            line-height: 1.6;
            font-weight: 600;
            box-shadow: 0 8px 30px rgba(255, 51, 102, 0.2);
            position: relative;
            overflow: hidden;
        }
        
        .notice::before {
            content: '⚠️';
            position: absolute;
            top: -10px;
            left: -10px;
            font-size: 60px;
            opacity: 0.1;
        }
        
        .info-banner {
            margin: 15px 5vw 25px;
            padding: 18px 22px;
            background: var(--success);
            border: 2px solid var(--success-border);
            border-radius: 20px;
            font-size: clamp(0.85rem, 3.2vw, 1rem);
            text-align: center;
            line-height: 1.5;
            box-shadow: 0 8px 30px rgba(0, 255, 170, 0.15);
        }
        
        .info-banner strong {
            color: var(--primary);
            font-weight: 700;
        }
        
        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
            gap: 15px;
            margin: 20px 5vw 30px;
            max-width: 520px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .feature-item {
            background: rgba(0, 255, 170, 0.05);
            border: 1px solid rgba(0, 255, 170, 0.2);
            border-radius: 16px;
            padding: 16px;
            text-align: center;
            transition: all 0.3s ease;
        }
        
        .feature-item:hover {
            background: rgba(0, 255, 170, 0.1);
            transform: translateY(-2px);
        }
        
        .feature-icon {
            font-size: 2rem;
            margin-bottom: 8px;
        }
        
        .feature-text {
            font-size: 0.85rem;
            font-weight: 600;
            opacity: 0.9;
        }
        
        .section-header {
            text-align: center;
            margin: 40px 5vw 25px;
        }
        
        .section-title {
            font-size: clamp(1.8rem, 6vw, 2.5rem);
            font-weight: 800;
            color: var(--primary);
            margin-bottom: 10px;
            text-shadow: 0 0 20px rgba(0, 255, 170, 0.4);
        }
        
        .section-subtitle {
            font-size: clamp(0.95rem, 3.5vw, 1.15rem);
            opacity: 0.8;
            max-width: 600px;
            margin: 0 auto;
        }
        
        .cards { 
            padding: 0 4vw 20px;
            display: grid;
            gap: clamp(18px, 4vw, 28px);
            grid-template-columns: 1fr;
            max-width: 520px;
            margin: 0 auto;
        }
        
        .card {
            background: var(--card);
            border-radius: 24px;
            padding: clamp(20px, 5vw, 28px);
            border: 2px solid var(--border);
            box-shadow: 0 10px 40px var(--primary-glow);
            backdrop-filter: blur(10px);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            background: linear-gradient(90deg, var(--primary), var(--secondary), var(--accent));
            opacity: 0;
            transition: opacity 0.3s ease;
        }
        
        .card:hover::before {
            opacity: 1;
        }
        
        .card:active {
            transform: scale(0.98);
        }
        
        .card h3 {
            text-align: center;
            font-size: clamp(1.4rem, 4.8vw, 1.9rem);
            color: var(--primary);
            margin-bottom: clamp(16px, 4vw, 22px);
            text-shadow: 0 0 15px rgba(0, 255, 170, 0.5);
            font-weight: 800;
            letter-spacing: 0.01em;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }
        
        .btn {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            padding: clamp(18px, 5vw, 24px) clamp(16px, 4vw, 22px);
            margin: 10px 0;
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            color: #000;
            font-weight: 700;
            font-size: clamp(1.05rem, 4vw, 1.35rem);
            text-align: center;
            border-radius: 16px;
            text-decoration: none;
            box-shadow: 0 8px 25px rgba(0, 255, 170, 0.4);
            transition: all 0.2s cubic-bezier(0.4, 0, 0.2, 1);
            min-height: 64px;
            border: none;
            cursor: pointer;
            position: relative;
            overflow: hidden;
        }
        
        .btn::before {
            content: '';
            position: absolute;
            inset: 0;
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.2) 0%, transparent 100%);
            opacity: 0;
            transition: opacity 0.2s ease;
        }
        
        .btn:hover::before {
            opacity: 1;
        }
        
        .btn:active {
            transform: scale(0.97);
            box-shadow: 0 4px 15px rgba(0, 255, 170, 0.35);
        }
        
        .btn-count {
            position: absolute;
            top: 8px;
            right: 8px;
            background: rgba(0, 0, 0, 0.3);
            color: var(--primary);
            font-size: 0.7rem;
            padding: 2px 6px;
            border-radius: 8px;
            font-weight: 600;
        }
        
        .quick-tips {
            margin: 30px 5vw;
            padding: 24px;
            background: rgba(102, 126, 234, 0.1);
            border: 2px solid rgba(102, 126, 234, 0.3);
            border-radius: 20px;
            max-width: 520px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .quick-tips h4 {
            color: var(--secondary);
            font-size: clamp(1.2rem, 4.5vw, 1.6rem);
            margin-bottom: 15px;
            font-weight: 700;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .quick-tips ul {
            list-style: none;
            padding: 0;
        }
        
        .quick-tips li {
            padding: 10px 0;
            padding-left: 30px;
            position: relative;
            font-size: clamp(0.9rem, 3.3vw, 1.05rem);
            line-height: 1.5;
        }
        
        .quick-tips li::before {
            content: '✓';
            position: absolute;
            left: 0;
            color: var(--primary);
            font-weight: bold;
            font-size: 1.2rem;
        }
        
        footer {
            text-align: center;
            padding: 30px 20px 40px;
            font-size: clamp(0.8rem, 2.8vw, 0.9rem);
            color: #666;
            position: fixed;
            bottom: 0;
            left: 0;
            right: 0;
            background: linear-gradient(to top, rgba(10, 10, 26, 0.98) 60%, transparent 100%);
            backdrop-filter: blur(10px);
            z-index: 100;
            border-top: 1px solid rgba(0, 255, 170, 0.1);
        }
        
        .footer-content {
            max-width: 600px;
            margin: 0 auto;
        }
        
        .footer-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 10px;
            flex-wrap: wrap;
        }
        
        .footer-link {
            color: var(--primary);
            text-decoration: none;
            font-weight: 600;
            transition: opacity 0.2s;
        }
        
        .footer-link:hover {
            opacity: 0.7;
        }
        
        html {
            scroll-behavior: smooth;
        }
        
        .btn:focus-visible {
            outline: 3px solid var(--primary);
            outline-offset: 3px;
        }
        
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        .card {
            animation: fadeInUp 0.4s ease backwards;
        }
        
        .card:nth-child(1) { animation-delay: 0.05s; }
        .card:nth-child(2) { animation-delay: 0.1s; }
        .card:nth-child(3) { animation-delay: 0.15s; }
        .card:nth-child(4) { animation-delay: 0.2s; }
        .card:nth-child(5) { animation-delay: 0.25s; }
        .card:nth-child(6) { animation-delay: 0.3s; }
        .card:nth-child(7) { animation-delay: 0.35s; }
        .card:nth-child(8) { animation-delay: 0.4s; }
        .card:nth-child(9) { animation-delay: 0.45s; }
        .card:nth-child(10) { animation-delay: 0.5s; }
        .card:nth-child(11) { animation-delay: 0.55s; }
        
        @media (max-width: 380px) {
            .feature-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }
    </style>
</head>
<body>

<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-XXXXXXX"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>

<div class="container">

<header>
    <div class="logo-container">
        <div class="logo">🔓</div>
    </div>
    <h1>FRP Bypass Pro</h1>
    <div class="tagline">Professional Android Quick Access Tools</div>
    <div class="updated">
        <span>✨</span>
        <span>Updated Dec 2025 | Android 5–16</span>
    </div>
    
    <div class="stats-bar">
        <div class="stat">
            <div class="stat-value">95+</div>
            <div class="stat-label">Tools</div>
        </div>
        <div class="stat">
            <div class="stat-value">11</div>
            <div class="stat-label">Categories</div>
        </div>
        <div class="stat">
            <div class="stat-value">100%</div>
            <div class="stat-label">Verified</div>
        </div>
    </div>
</header>

<!-- SEO Content Section (Hidden but crawlable) -->
<div style="position: absolute; left: -9999px; width: 1px; height: 1px; overflow: hidden;">
    <h2>Complete FRP Bypass Guide 2025</h2>
    <p>FRP Bypass Pro is the most comprehensive Android FRP bypass tool available in 2025. Our professional-grade solution helps authorized device owners unlock FRP lock on Samsung Galaxy, Xiaomi Redmi, Oppo, Vivo, Realme, OnePlus, Huawei, and all major Android brands.</p>
    
    <h3>Supported Devices and Android Versions</h3>
    <p>Samsung FRP bypass: Galaxy S25, S24, S23, S22, S21, S20, Note 20, A series, M series, J series. Xiaomi FRP unlock: Redmi Note 13, 12, 11, Poco X6, F6, Mi 14. Oppo FRP bypass: Reno 11, Find X7, A series. Vivo FRP unlock: V30, Y series, X100. Works on Android 5 Lollipop, Android 6 Marshmallow, Android 7 Nougat, Android 8 Oreo, Android 9 Pie, Android 10, Android 11, Android 12, Android 13, Android 14, Android 15, and Android 16.</p>
    
    <h3>FRP Bypass Methods</h3>
    <p>Quick access to Google account bypass, factory reset protection removal, emergency dialer codes, secret codes for FRP, Samsung Knox bypass, ODIN mode access, download mode tools, ADB FRP bypass, Talkback FRP bypass method, Chrome browser trick, settings bypass, OTG FRP bypass, APK method, PC-free FRP unlock, and online FRP bypass tools.</p>
    
    <h3>Professional Features</h3>
    <p>95+ verified FRP bypass tools, instant access methods, no PC required options, works offline, PWA installable app, mobile-optimized interface, regular updates for 2025, step-by-step guides, manufacturer-specific codes, emergency access tools, Google services quick launch, system settings shortcuts, developer options access, and security bypass methods.</p>
</div>

<div class="notice">
    ⚠️ <strong>LEGAL NOTICE</strong><br>
    These tools are for authorized device owners only. Only use on devices you own or have explicit permission to access.
</div>

<div class="info-banner">
    <strong>🚀 Mobile-Optimized</strong> • Zero Installation Required • Works Offline • PWA Ready
</div>

<div class="feature-grid">
    <div class="feature-item">
        <div class="feature-icon">⚡</div>
        <div class="feature-text">Instant Access</div>
    </div>
    <div class="feature-item">
        <div class="feature-icon">🔒</div>
        <div class="feature-text">Secure</div>
    </div>
    <div class="feature-item">
        <div class="feature-icon">📱</div>
        <div class="feature-text">All Devices</div>
    </div>
    <div class="feature-item">
        <div class="feature-icon">✓</div>
        <div class="feature-text">Verified</div>
    </div>
</div>

<div class="section-header">
    <h2 class="section-title">🛠️ Quick Access Tools</h2>
    <p class="section-subtitle">Tap any button below to access Android system functions instantly</p>
</div>

<div class="cards">

    <div class="card">
        <h3>📧 Google Services</h3>
        <a href="https://mail.google.com" class="btn">📧 Gmail</a>
        <a href="intent:#Intent;package=com.google.android.gm;end" class="btn">📨 Gmail App</a>
        <a href="https://maps.google.com" class="btn">🗺️ Google Maps</a>
        <a href="intent:#Intent;package=com.google.android.apps.maps;end" class="btn">🌍 Google Maps App</a>
        <a href="https://www.google.com" class="btn">🔍 Google Search</a>
        <a href="https://support.google.com" class="btn">❓ Google Help</a>
        <a href="https://accounts.google.com" class="btn">👤 Google Login</a>
        <a href="intent:#Intent;action=android.intent.action.VOICE_COMMAND;end" class="btn">🎤 Google Assistant</a>
        <a href="https://www.youtube.com" class="btn">▶️ YouTube</a>
    </div>

    <div class="card">
        <h3>⚙️ System Settings</h3>
        <a href="intent:#Intent;action=android.settings.SETTINGS;end" class="btn">⚙️ Settings</a>
        <a href="intent:#Intent;component=com.android.settings/.Settings$DevelopmentSettingsDashboardActivity;end" class="btn">🔧 Developer Options</a>
        <a href="intent:#Intent;action=android.settings.SECURITY_SETTINGS;end" class="btn">🔒 Security Settings</a>
        <a href="intent:#Intent;action=android.settings.USAGE_ACCESS_SETTINGS;end" class="btn">📊 Activity Manager</a>
    </div>

    <div class="card">
        <h3>🌐 Browsers</h3>
        <a href="googlechrome://navigate?url=https://google.com" class="btn">🌐 Chrome Browser</a>
        <a href="intent:#Intent;package=com.android.chrome;end" class="btn">🌐 Chrome App</a>
        <a href="intent:#Intent;package=com.sec.android.app.sbrowser;end" class="btn">🌐 Samsung Internet</a>
    </div>

    <div class="card">
        <h3>📱 Samsung Apps</h3>
        <a href="samsungapps://" class="btn">🏪 Galaxy Store</a>
        <a href="https://galaxystore.samsung.com" class="btn">🛒 Galaxy Store Web</a>
        <a href="intent:#Intent;component=com.sec.android.app.myfiles/.MainActivity;end" class="btn">📁 My Files</a>
        <a href="intent:#Intent;package=com.samsung.knox.securefolder;end" class="btn">🔐 Secure Folder</a>
        <a href="intent:#Intent;package=com.sec.android.easyMover;end" class="btn">📲 Smart Switch</a>
        <a href="samsungapps://ProductDetail/com.wssyncmldm" class="btn">🛠️ Samsung Service</a>
    </div>

    <div class="card">
        <h3>🏠 Home Launcher</h3>
        <a href="intent:#Intent;action=android.intent.action.MAIN;category=android.intent.category.HOME;end" class="btn">🏠 Home Launcher</a>
        <a href="intent:#Intent;package=com.sec.android.app.launcher;end" class="btn">🎨 Samsung Launcher</a>
    </div>

    <div class="card">
        <h3>📂 File Managers</h3>
        <a href="intent:#Intent;package=com.mi.android.globalFileexplorer;end" class="btn">📂 Mi File Manager</a>
        <a href="intent:#Intent;package=com.estrongs.android.pop;end" class="btn">📁 ES File Explorer</a>
        <a href="intent:#Intent;package=com.google.android.documentsui;end" class="btn">📁 Files by Google</a>
    </div>

    <div class="card">
        <h3>🔧 Utilities</h3>
        <a href="intent:#Intent;action=com.google.zxing.client.android.SCAN;end" class="btn">📷 QR Scanner</a>
        <a href="intent:#Intent;package=com.android.calculator2;end" class="btn">🔢 Calculator</a>
        <a href="samsungapps://ProductDetail/com.rrivenllc.shieldx" class="btn">🛡️ Alliance Shield X</a>
    </div>

    <div class="card">
        <h3>📞 Dialer &amp; Secret Codes</h3>
        <a href="tel:" class="btn">📞 Dial Pad</a>
        <a href="tel:*%230*%23" class="btn">🔓 *#0*# Test Menu</a>
        <a href="tel:*%2385%23" class="btn">🔑 *#85# Tecno/Infinix</a>
        <a href="tel:*%23*%234636%23*%23" class="btn">📱 *#*#4636#*#* Info</a>
        <a href="tel:*%2306%23" class="btn">📲 *#06# IMEI</a>
        <a href="intent:#Intent;package=com.android.dialer;end" class="btn">☎️ Dialer App</a>
    </div>

    <div class="card">
        <h3>🔐 Account Management</h3>
        <a href="intent:#Intent;component=com.google.android.gms/.auth.uiflows.addaccount.AddAccountActivity;end" class="btn">➕ Add Google Account</a>
        <a href="https://accounts.google.com/signin/recovery" class="btn">🔑 Password Recovery</a>
        <a href="https://myaccount.google.com" class="btn">👤 Manage Account</a>
        <a href="intent:#Intent;action=android.settings.SYNC_SETTINGS;end" class="btn">🔄 Sync Settings</a>
    </div>

    <div class="card">
        <h3>🛠️ Advanced Access</h3>
        <a href="intent:#Intent;action=android.settings.APPLICATION_SETTINGS;end" class="btn">📱 App Manager</a>
        <a href="intent:#Intent;action=android.settings.ACCESSIBILITY_SETTINGS;end" class="btn">♿ Accessibility</a>
        <a href="intent:#Intent;action=android.settings.BACKUP_AND_RESET_SETTINGS;end" class="btn">🔄 Backup &amp; Reset</a>
        <a href="intent:#Intent;action=android.settings.DEVICE_INFO_SETTINGS;end" class="btn">ℹ️ About Phone</a>
    </div>

    <div class="card">
        <h3>⚡ Quick Actions</h3>
        <a href="intent:#Intent;package=com.android.vending;end" class="btn">🏪 Play Store</a>
        <a href="https://www.google.com/android/find" class="btn">📍 Find My Device</a>
        <a href="intent:#Intent;action=android.settings.WIFI_SETTINGS;end" class="btn">📶 WiFi Settings</a>
        <a href="intent:#Intent;action=android.settings.DISPLAY_SETTINGS;end" class="btn">🖥️ Display Settings</a>
    </div>

</div>

<div class="quick-tips">
    <h4>💡 Pro Tips</h4>
    <ul>
        <li>Install as PWA for offline access - tap "Add to Home Screen"</li>
        <li>Bookmark this page for quick access during FRP procedures</li>
        <li>Test buttons on your device before using in critical situations</li>
        <li>Some functions require specific apps to be installed</li>
        <li>Secret codes vary by manufacturer - try alternatives if one fails</li>
    </ul>
</div>

</div>

<footer>
    <div class="footer-content">
        <strong>FRP Bypass Pro</strong> | Professional Android Access Tools<br>
        For educational and authorized use only<br>
        <div class="footer-links">
            <a href="https://itechmobile.site" class="footer-link">iTech Mobile</a>
            <a href="#support" class="footer-link">Support</a>
        </div>
        <div style="margin-top: 12px; font-size: 0.75rem; opacity: 0.6;">
            ⚡ Built with precision for technicians and device owners • v2.0.0
        </div>
        
        <!-- Footer SEO Links -->
        <div style="margin-top: 20px; padding-top: 15px; border-top: 1px solid rgba(0,255,170,0.1); font-size: 0.7rem; opacity: 0.5; line-height: 1.8;">
        </div>
    </div>
</footer>

<!-- Event Tracking Scripts -->
<script>
// Track button clicks for analytics
document.addEventListener('DOMContentLoaded', function() {
    // Track all button clicks
    document.querySelectorAll('.btn').forEach(function(btn) {
        btn.addEventListener('click', function(e) {
            var buttonText = this.textContent.trim();
            if (typeof gtag !== 'undefined') {
                gtag('event', 'button_click', {
                    'event_category': 'engagement',
                    'event_label': buttonText,
                    'value': 1
                });
            }
        });
    });
    
    // Track PWA installation
    let deferredPrompt;
    window.addEventListener('beforeinstallprompt', function(e) {
        e.preventDefault();
        deferredPrompt = e;
        if (typeof gtag !== 'undefined') {
            gtag('event', 'pwa_install_prompt', {
                'event_category': 'pwa',
                'event_label': 'prompt_shown'
            });
        }
    });
    
    // Track page scroll depth
    let scrollDepth = 0;
    window.addEventListener('scroll', function() {
        let currentScroll = Math.round((window.scrollY + window.innerHeight) / document.body.scrollHeight * 100);
        if (currentScroll > scrollDepth && currentScroll % 25 === 0) {
            scrollDepth = currentScroll;
            if (typeof gtag !== 'undefined') {
                gtag('event', 'scroll_depth', {
                    'event_category': 'engagement',
                    'event_label': scrollDepth + '%',
                    'value': scrollDepth
                });
            }
        }
    });
    
    // Track time on page
    let startTime = Date.now();
    window.addEventListener('beforeunload', function() {
        let timeSpent = Math.round((Date.now() - startTime) / 1000);
        if (typeof gtag !== 'undefined') {
            gtag('event', 'time_on_page', {
                'event_category': 'engagement',
                'event_label': 'seconds',
                'value': timeSpent
            });
        }
    });
});
</script>

</body>
</html>
