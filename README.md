# Browser-Based PDF Unlocker

A 100% private, offline, WASM-powered tool to remove passwords from encrypted PDFs (including modern AES-256).

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

## Credits & Technologies
- **QPDF**: This tool is built on [QPDF](https://github.com/qpdf/qpdf), a phenomenal C++ library and command-line program that does structural, content-preserving transformations on PDF files.
- **WASM Port**: The WebAssembly port ([qpdf-wasm](https://github.com/neslinesli93/qpdf-wasm)) was created by [@neslinesli93](https://github.com/neslinesli93). Their work enables running QPDF entirely within the browser!

## License
MIT License
