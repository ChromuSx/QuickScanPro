# 📸 QuickScanPro

## Overview

QuickScanPro is a PowerShell script designed to facilitate the scanning of documents and photos, especially Polaroid pictures. It allows users to easily convert scanned images into PDF format. With a simple command-line interface for Windows PowerShell, QuickScanPro integrates external dependencies to enhance functionality, ensuring an efficient and flexible user experience.

## ✨ Features

- **Polaroid and Full-Page Scanning**: Choose between scanning individual Polaroid photos or full pages.
- **DPI Selection**: Select the desired DPI (Dots Per Inch) for your scans, with options of **300 DPI**, **600 DPI**, and **1200 DPI**.
- **Post-Scan Options**: After a scan, you can repeat it with the same settings, start a new scan, or exit the application.
- **PDF Conversion**: Automatically convert scanned images to PDF format, with the image adjusted to fit the page.

## 📋 Prerequisites

- **Windows PowerShell**
- **BouncyCastle.Crypto.dll** and **itextsharp.dll** libraries

## 🚀 Installation

Before running QuickScanPro, you need to download and prepare the external libraries (**BouncyCastle.Crypto.dll** and **itextsharp.dll**) needed for the script to work.

### Preparing External Libraries

- **BouncyCastle.Crypto.dll**
  1. Download the library from "The Legion of the Bouncy Castle."
  2. Specifically, download **bccrypto-csharp-1.8.9-bin.zip** from the release dated 9th December 2020.
  3. Extract the ZIP file and locate the DLL in the **lib** folder.
  4. Place the DLL in the same directory as the **QuickScanPro.ps1** script.

- **iTextSharp.dll**
  1. Download the iTextSharp package from NuGet by clicking on "Download package."
  2. Change the downloaded file's extension from **.nupkg** to **.zip**.
  3. Extract the ZIP file and locate the DLL in the **lib** folder.
  4. Place the DLL in the same directory as the **QuickScanPro.ps1** script.

### Installing the Script

1. **Clone** this repository or **download** the **QuickScanPro.ps1** script directly to your computer.
2. Ensure the **BouncyCastle.Crypto.dll** and **itextsharp.dll** libraries are in the same directory as the script.

## ▶️ Running the Script

1. Open PowerShell in the directory containing the script and the required DLL files.
2. Execute the script by typing `.\QuickScanPro.ps1` or double-clicking on the script file.
3. Follow the on-screen prompts to select scanning options and process your documents or photos.

## 🤝 Contributing

Contributions are welcome! If you have a feature request, bug report, or want to submit a pull request, please follow these steps:

1. **Fork** the repository.
2. **Create a new branch** for your feature or fix.
3. **Commit** your changes.
4. **Push** to your branch.
5. Submit a **pull request**.

## 📜 License

This project is open-source and available under the **MIT License**.

## 🙏 Acknowledgements

Special thanks to the creators of the **iTextSharp** and **BouncyCastle** libraries for providing the essential tools needed for PDF conversion.

