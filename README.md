
# Canteen-go

Low-cost two-way Braille reader and embosser with optical reading, OCR-to-Braille conversion, Bluetooth communication, and automatic paper alignment.

## Overview

Canteen-go is an affordable, portable device that bridges the gap between printed/digital text and Braille. It can:
- **Read** printed text optically and convert it to Braille output in real time
- **Emboss** Braille onto paper for physical, reusable documents
- **Communicate** wirelessly via Bluetooth with phones/computers
- **Auto-align** paper feed for consistent, accurate embossing without manual adjustment

Designed to make Braille technology accessible at a fraction of the cost of commercial devices.

## Features

- 🔤 Optical Character Recognition (OCR) for printed text
- ⠿ Real-time text-to-Braille translation
- 🖨️ Mechanical Braille embosser
- 📶 Bluetooth connectivity for two-way communication
- 📄 Automatic paper feed and alignment system
- 💰 Low-cost, accessible hardware design

## How It Works

1. **Capture** – A camera/optical sensor scans printed text
2. **Recognize** – OCR extracts readable characters from the image
3. **Translate** – Text is converted into Grade 1/2 Braille encoding
4. **Emboss** – The mechanical embosser punches the Braille pattern onto paper
5. **Sync** – Bluetooth module allows sending/receiving text from a paired device

## Hardware

| Component | Purpose |
|---|---|
| Microcontroller (e.g., ESP32/Arduino) | Core processing + Bluetooth |
| Camera module | Optical text capture |
| Stepper motors | Paper alignment & embossing head movement |
| Embossing pins/solenoids | Physical Braille dot punching |
| Power supply | Portable operation |

*(Update with your actual BOM)*

## Software / Tech Stack

- Firmware: [language, e.g., C++/Arduino/MicroPython]
- OCR engine: [e.g., Tesseract, custom model]
- Braille translation: [library/algorithm used]
- Bluetooth protocol: [e.g., SPP, BLE]

## Getting Started

### Prerequisites
- [List required tools, SDKs, libraries]

### Installation
```bash
git clone https://github.com/yourusername/Canteen-go.git
cd Canteen-go
# build/flash instructions
```

### Usage
- [How to power on, pair Bluetooth, feed paper, start scanning, etc.]

## Project Status

🚧 In development — [mention current stage: prototype, testing, etc.]

## Roadmap

- [ ] Improve OCR accuracy for varied fonts
- [ ] Support Grade 2 Braille contractions
- [ ] Mobile app companion
- [ ] Reduce embosser noise/cost

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

[Specify license, e.g., MIT]

## Acknowledgments

- [Credit any libraries, papers, or inspirations]
