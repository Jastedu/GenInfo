# GenInfo
Guided wizard to generate standardized business reports with PDF export, evidence tracking, and digital/Hash signatures.

# 📄 GenInfo: Standardized Report Generator

An interactive micro-app designed to streamline the creation, structuring, and signing of technical and business reports. This tool guides the user step-by-step to gather work details and evidence, ultimately generating a fully formatted PDF document that complies with specific standards.

## 🎯 The Problem it Solves
Report writing often consumes hours of repetitive formatting and standardization tasks. This application removes administrative friction through a guided flow (wizard), ensuring that all documents from a team or department meet the same structure and regulatory standards before being exported and signed.

## ✨ Key Features

*   **Guided Wizard:** A step-by-step interface that prompts the author for work details, activities performed, and conclusions.
*   **Template & Standards Management:** Allows users to select the document standard (e.g., APA, ISO, or custom corporate templates).
*   **Evidence Attachment:** Module to upload and reference backing images or documents directly within the report.
*   **PDF Export:** Instant generation of the final document with a professional layout, ready for distribution.
*   **Signature Module:** Supports authorship validation via drawn signature (mouse/touchscreen) or a cryptographic Hash validation.
*   **Smart Categorization:** Save and organize generated reports by author and department (base architecture ready to be connected to a robust database).

## 🛠️ Tech Stack

*   **Frontend / UI:** React
*   **Backend / Logic:** Python (Flask)
*   **PDF Generation:** ReportLab
*   **Digital Signature:** Native Cryptography (HASH) & HTML5 Canvas API for manual signatures.

## 🚀 Installation and Local Setup

This project is divided into two main environments: the Flask backend and the React frontend. Follow these steps to run it locally:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Jastedu/GenInfo.git](https://github.com/Jastedu/GenInfo.git)
   cd GenInfo



🤝 Contributing and Scalability
This project is built with a modular architecture. Interested developers can easily fork and extend its features (for example, integrating cloud storage like AWS S3, connecting PostgreSQL databases for user management, or adding new export standards).

Pull Requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details. You are free to use, modify, and distribute this software, even for commercial purposes, as long as the original copyright notice is included.
