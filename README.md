# NGO GRC Toolkit

A free, browser-based tool to help NGOs build an ISO 27001 Risk Register and a Data Protection Impact Assessment (DPIA).

![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)
![Version](https://img.shields.io/badge/Version-3.2-brightgreen.svg)
![Tech](https://img.shields.io/badge/Tech-HTML%2C%20CSS%2C%20JS-yellow.svg)

[![Try it Live on CodePen](https://img.shields.io/badge/CodePen-Live%20Demo-blue?style=for-the-badge&logo=codepen)](https://codepen.io/Mathias-Hagstrom/full/JoYzQeL)

---

## About This Project

The NGO GRC Toolkit is a guided, step-by-step application designed to simplify the complex but crucial process of risk management for Non-Governmental Organizations. Many NGOs handle highly sensitive data but may not have the resources for expensive Governance, Risk, and Compliance (GRC) software. This tool bridges that gap by providing a simple, effective, and completely free solution.

**Most importantly, your privacy is paramount.** This tool runs entirely in your web browser. No data is ever sent to a server, and no cookies are used. Your information remains on your computer at all times.

Click the Codepen live demo button above this section to try it out!
## Key Features

* **Guided 4-Step Process:** A simple wizard that walks you through creating your GRC documentation.
* **ISO 27001 Risk Register:** Identify assets, define risks, and map them to the official ISO 27001:2022 Annex A controls.
* **DPIA Questionnaire:** A straightforward Data Protection Impact Assessment to help you comply with privacy regulations like GDPR.
* **Session Management:** Save your progress to a local file at any time and load it back up to continue your work.
* **Data Export:** Download your complete GRC report as a professional PDF or your risk register data as a CSV file.
* **CSV Import & Duplicate Finder:** Quickly import existing risks and scan your register for duplicates.
* **Online & Offline Versions:** Use the simple online version or download the full package for offline use.

## Getting Started

Choose the version that best suits your needs from the [**Releases Page**](https://github.com/maheha/NGO-GRC-Toolkit/releases).

---

### Option 1: Online Version (Simple, requires internet)

This is the easiest way to get started if you have a reliable internet connection.

* **File:** `toolkit.html`
* **To use:**
    1.  Download the `toolkit.html` file from the latest release.
    2.  Open it in a modern web browser (like Chrome or Firefox).
    3.  **An internet connection is required.**

---

### Option 2: Offline Package (Works without internet)

Use this version if you need to work on the toolkit without an internet connection.

* **File:** `NGO-GRC-Toolkit-Offline.zip`
* **To use:**
    1.  Download the `.zip` file from the latest release.
    2.  **Unzip/extract** the file on your computer. This will create a folder.
    3.  Open the folder and double-click the `toolkit-offline.html` file to open it in your browser.
    4.  **No internet connection is required.**

## For Developers (Technical Details)

This project is intentionally built as a "vanilla" single-page application to ensure maximum portability and simplicity. The offline version includes local copies of all dependencies.

### Tech Stack

* **HTML5:** For the core structure.
* **Tailwind CSS:** For all styling.
* **JavaScript (ES6+):** All application logic is contained within a single `<script>` tag.
* **jsPDF & jsPDF-AutoTable:** Used for the PDF export functionality.

## Contributing

Contributions are welcome! If you have an idea for a new feature or find a bug, please follow these steps:

1. Open an issue on GitHub to discuss the proposed changes.
2. Fork the repository and create a new branch for your feature.
3. Submit a pull request with a clear description of your changes.

## License

This project is open-source and released under the GNU General Public License v3.0.

## Contact

Created and maintained by **Mathias Hagstrøm**.
* **Email:** maheha@gmail.com
