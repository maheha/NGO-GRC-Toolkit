# NGO GRC Toolkit

A free, browser-based tool to help NGOs build an ISO 2701 Risk Register and a Data Protection Impact Assessment (DPIA).

![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)
![Version](https://img.shields.io/badge/Version-3.2-brightgreen.svg)
![Tech](https://img.shields.io/badge/Tech-HTML%2C%20CSS%2C%20JS-yellow.svg)

---

## About This Project

The NGO GRC Toolkit is a guided, step-by-step application designed to simplify the complex but crucial process of risk management for Non-Governmental Organizations. Many NGOs handle highly sensitive data but may not have the resources for expensive Governance, Risk, and Compliance (GRC) software. This tool bridges that gap by providing a simple, effective, and completely free solution.

**Most importantly, your privacy is paramount.** This tool runs entirely in your web browser. No data is ever sent to a server, and no cookies are used. Your information remains on your computer at all times.

## Key Features

* **Guided 4-Step Process:** A simple wizard that walks you through creating your GRC documentation.
* **ISO 2701 Risk Register:** Identify assets, define risks, and map them to the official ISO 2701:2022 Annex A controls.
* **DPIA Questionnaire:** A straightforward Data Protection Impact Assessment to help you comply with privacy regulations like GDPR.
* **Session Management:** Save your progress to a local file at any time and load it back up to continue your work.
* **Data Export:** Download your complete GRC report as a professional PDF or your risk register data as a CSV file for use in other programs.
* **CSV Import:** Already have a list of risks? Import them directly from a CSV file to get started quickly.
* **Duplicate Finder:** A handy utility to scan your risk register for potential duplicate entries.

## Getting Started (For All Users)

Using the toolkit is simple. You just need a modern web browser and an internet connection.

1.  Navigate to the **[Releases Page](https://github.com/your-username/your-repo-name/releases)** (link to be updated).
2.  Download the `toolkit.html` file from the latest release.
3.  Open the downloaded `toolkit.html` file in your web browser (like Chrome, Firefox, or Edge).

**Note:** An active internet connection is required because the tool loads its styling (Tailwind CSS) and PDF generation libraries from a secure Content Delivery Network (CDN). This keeps the file size small and ensures you're always using an up-to-date version of those libraries.

## For Developers (Technical Details)

This project is intentionally built as a "vanilla" single-page application to ensure maximum portability and simplicity.

### Tech Stack

* **HTML5:** For the core structure.
* **Tailwind CSS:** For all styling, loaded via CDN.
* **JavaScript (ES6+):** All application logic is contained within a single `<script>` tag. There are no external frameworks or libraries, keeping it lightweight and easy to understand.
* **jsPDF & jsPDF-AutoTable:** Used for the PDF export functionality, loaded via CDN.

### Project Structure

The entire application is contained within a single `toolkit.html` file. This was a deliberate design choice to make it incredibly easy for non-technical users to download and run without needing a web server or complex setup.

### Contributing

Contributions are welcome! If you have an idea for a new feature or find a bug, please follow these steps:

1.  Open an issue on GitHub to discuss the proposed changes.
2.  Fork the repository and create a new branch for your feature.
3.  Submit a pull request with a clear description of your changes.

## License

This project is open-source and released under the GNU General Public License v3.0. The full license text is available in the comment block at the top of the `toolkit.html` file.

## Contact

Created and maintained by **Mathias Hagstrøm**.
* **Email:** maheha@gmail.com
