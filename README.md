# NeoScan - Futuristic AI QR Scanner

NeoScan is a **futuristic, real-time AI-powered QR code scanner** that runs entirely in the browser. It detects QR codes using your device camera, classifies them as safe or unsafe based on URL heuristics, and provides instant feedback with an aesthetic, minimalistic UI.

## Features

* **Real-time QR scanning** using the camera.
* **Safety classification** for URLs using basic heuristics:

  * Detects common shorteners like `bit.ly`, `tinyurl`, `goo.gl`.
  * Ensures URLs are valid and properly formatted.
* **Visual feedback**:

  * Green border for safe QR codes.
  * Red border for unsafe QR codes.
* **Go to link button**:

  * Appears only for safe URLs.
  * Automatically disappears 5 seconds after the last QR scan.
* **Minimalistic and futuristic UI**:

  * Neon-inspired color theme.
  * Smooth border glow effects.
* **Fully client-side**:

  * Runs entirely in the browser.
  * No backend or server required.
  * Can be hosted on GitHub Pages or any static site host.

## Get Started with NeoScan

* **Online Access:** Open NeoScan directly in your browser using [this link](https://abhivandan7.github.io/NeoScan/).

* **Mobile Widget:** For faster access, add NeoScan to your phone’s home screen:

  * **iOS Safari:** Tap **Share → Add to Home Screen**.
  * **Android Chrome:** Tap **Menu → Add to Home screen**.

* **Local Use:** Download the repository and open `index.html` in a modern browser.

* **Tip:** Allow camera access to start real-time scanning instantly.

## Usage

1. Open the application in your browser.
2. Allow camera access when prompted.
3. Point your device camera at a QR code.
4. The border around the scanner window will glow green if the QR is safe, or red if unsafe.
5. For safe QR codes, a button will appear at the bottom with the link. Click to navigate to the URL.
6. If the QR is no longer detected, the last link remains visible for 5 seconds before disappearing.

## Technical Details

* **QR Code Detection**: [jsQR](https://github.com/cozmo/jsQR) library.
* **Client-side AI Logic**: Basic URL heuristics; can be extended with more advanced ML/LLM models.
* **UI**: HTML, CSS with neon/futuristic styling, minimalistic and responsive.
* **Browser Support**: Modern browsers with `getUserMedia` API support (Chrome, Edge, Firefox).

## Future Enhancements

* Integrate **real AI/ML models** for detecting sophisticated malicious URLs.
* Include **LLM-powered analysis** for phishing detection.
* Improve UI with **dynamic animations** and enhanced futuristic effects.
* Add **QR history log** for previously scanned codes.

## License

NeoScan is released under the **Apache 2.0 License**. You are free to use, modify, and distribute it.

## Screenshots

![NeoScan_Good_QR Screenshot](uploads/Screenshot from 2025-12-14 20-12-05.png)
![NeoScan Bad_QR Screenshot]("uploads/Screenshot from 2025-12-14 20-14-35.png")

---

**NeoScan** - Your futuristic companion for safe QR code scanning.
