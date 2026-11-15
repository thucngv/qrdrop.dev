# QRDrop
> **Offline File Transfer via QR Codes**

[QRDrop](https://qrdrop.dev/) is a web application designed for environments where traditional connections are unavailable or restricted. It allows you to transfer files from your computer to an Android phone or iPhone using **only the computer screen and the phone’s camera**. 

No network connection, USB connection, or Bluetooth is required.

---

## 🎬 Demo Video

<div align="center">
  <a href="https://www.youtube.com/shorts/gJ2YX5hCujs">
    <img src="https://img.youtube.com/vi/gJ2YX5hCujs/maxresdefault.jpg" alt="QRDrop Demo" width="60%" style="border-radius: 12px; border: 1px solid #30474d;" />
  </a>
  <p><em>Click to watch the QRDrop demo on YouTube Shorts</em></p>
</div>

---

## 🚀 How It Works

QRDrop displays the selected file as a series of QR codes directly in your browser. 

1. **Choose a file** on your computer (supports files up to 16 MiB, processed locally in your browser).
2. **Scan the first QR code** using the QRDrop app on your mobile device.
3. **Play the sequence** and keep your phone pointed at the screen until the app finishes receiving the file. Playback automatically loops so the app can catch any missed codes.

> **Note on Performance:** The trade-off for offline/restricted transfers is slower speeds, especially for larger files, because the phone has to scan the QR codes one at a time. Transfer speed and reliability depend on the scanning phone, ambient lighting, and your screen.

---

## 🎛️ Transfer Settings & Features

* **Data per QR Code (Density)**: Choose how much data is packed into each frame, ranging from *Easy to scan (128 bytes)* up to *Maximum (2,953 bytes including header)*.
* **Time per QR Code (Speed)**: Adjust the playback speed from 50 ms up to 5 seconds per frame.
* **Compression**: Optimize payloads using `Off`, `GZIP`, or `Auto` (tries GZIP and Brotli).
* **Playback Controls**: Use *Play*, *Previous*, *Next*, *Full screen*, or jump directly to a specific part index.

---

## 📱 Get the QRDrop Mobile App

To scan and receive files transferred from your computer, download the official QRDrop mobile app:

* [Get it on Google Play](https://play.google.com/store/apps/details?id=com.thucnv.qrdrop)
* [Download on the App Store](https://apps.apple.com/app/id6833968959)

---

## 📦 Basic Offline Version

If you need a standalone setup, you can use the basic offline version:
* Download or copy the standalone HTML file ([qrdrop-basic.html](qrdrop-basic.html)) and open it directly in any browser to send files offline without an internet connection.

---

## 📄 Privacy

* **Privacy Policy**: Read the [Privacy Policy](./privacy.html) for details on data handling.
