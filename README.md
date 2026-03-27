# Browser-Based PDF Unlocker

A 100% private, offline, WASM-powered tool to remove passwords from encrypted PDFs (including modern AES-256).

🚀 **[Try it live here!](https://rajmahavir.github.io/pdf-unlocker/)**

## Features
- **Client-Side Processing**: Entirely powered by WebAssembly (WASM).
- **Private & Secure**: No server uploads required; your files never leave your device.
- **Modern Standards**: Full support for AES-256 encryption.
- **Easy to Use**: Simple drag-and-drop interface.

## Usage
1. Open `index.html` in any modern web browser.
2. Drag and drop your encrypted PDF file into the designated area.
3. Enter the known password for the PDF.
4. Click to immediately remove the password and download the unlocked version.

## Legal Disclaimer
This tool is provided for **personal convenience, free of charge**, to help users remove password protection from their own documents (e.g., bank statements, pay stubs, event tickets) where they already possess the legitimate password.

It does **not** brute-force or "crack" unknown passwords. It simply automates the process of entering your known password and saving an unencrypted copy locally. Bypassing DRM on documents you do not own or do not have the right to access may violate copyright laws (such as the DMCA). Please use responsibly and only on your own files!

## Credits & Technologies
- **QPDF**: This tool is built on [QPDF](https://github.com/qpdf/qpdf), a phenomenal C++ library and command-line program that does structural, content-preserving transformations on PDF files.
- **WASM Port**: The WebAssembly port ([qpdf-wasm](https://github.com/neslinesli93/qpdf-wasm)) was created by [@neslinesli93](https://github.com/neslinesli93). Their work enables running QPDF entirely within the browser!

## License
MIT License
