# QuickScanPro

## Overview
The QuickScanPro PowerShell script is designed to facilitate the scanning of documents and photos, particularly Polaroid pictures. It offers users the flexibility to convert scanned images into PDF format if desired. The script provides an easy-to-use command-line interface for Windows PowerShell, integrating with external dependencies for processing. This flexibility ensures that QuickScanPro can cater to various user needs, whether it's preserving the original scan format or opting for the convenience of PDFs.

## Features
- **Polaroid and Full-Page Scanning:** Offers the option to scan either individual Polaroid photos or full pages.
- **DPI Selection:** Allows users to choose the desired DPI (Dots Per Inch) for the scan, offering 300 DPI, 600 DPI, and 1200 DPI options.
- **Post-Scan Options:** Users can choose to repeat a scan with the same settings, start a new scan with different settings, or exit the application.
- **PDF Conversion:** Automatically converts scanned images to PDF format, adjusting the image to fit the page size.

## Prerequisites
- Windows PowerShell
- The `BouncyCastle.Crypto.dll` and `itextsharp.dll` libraries

## Installation
Before you begin, you will need to download and prepare the external libraries (`BouncyCastle.Crypto.dll` and `itextsharp.dll`) required for this script to function.

### Preparing External Libraries
1. **BouncyCastle.Crypto.dll**
   - Download the library from [The Legion of the Bouncy Castle](https://www.bouncycastle.org/csharp/).
   - Specifically, download `bccrypto-csharp-1.8.9-bin.zip` under the Release 1.8.9, dated 9th December 2020.
   - Extract the ZIP file and navigate to the `lib` folder to find the DLL.
   - Place the DLL in the same directory as the `QuickScanPro.ps1` script.

2. **iTextSharp.dll**
   - Download the iTextSharp package from [NuGet](https://www.nuget.org/packages/iTextSharp) by clicking on "Download package".
   - Change the downloaded file's extension from `.nupkg` to `.zip`.
   - Extract the ZIP file and navigate to the `lib` folder to find the DLL.
   - Place the DLL in the same directory as the `QuickScanPro.ps1` script.

### Installing the Script
1. Clone this repository or download the `QuickScanPro.ps1` script directly to your computer.
2. Ensure the `BouncyCastle.Crypto.dll` and `itextsharp.dll` libraries are placed in the same directory as the script.

### Running the Script
1. Open PowerShell in the directory containing the script and the required DLL files.
2. Execute the script by typing `.\QuickScanPro.ps1` or simply open the script by double-click.
3. Follow the on-screen prompts to select the scanning options and process your documents or photos.

## Contributing
Contributions to the QuickScanPro script are welcome. If you have a feature request, bug report, or a pull request, please feel free to contribute. Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Commit your changes.
4. Push to your branch.
5. Submit a pull request.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgements
Special thanks to the creators of the iTextSharp and BouncyCastle libraries for providing the essential tools needed for PDF conversion.

