# HTTP Server with QR Code Access

This project demonstrates how to create a simple HTTP server in Python that serves files from your desktop and generates a QR code to easily access the server from other devices. The server is implemented using the `http.server`, `socket`, and `socketserver` modules, and the QR code is generated using the `pyqrcode` and `png` modules. 

## Features

- Serve files from your desktop over HTTP.
- Generate a QR code that links to the HTTP server.
- Automatically open the QR code in the default web browser.

## Getting Started

### Prerequisites

- Python 3.x installed on your system.
- The following Python modules:
  - `http.server`
  - `socket`
  - `socketserver`
  - `webbrowser`
  - `pyqrcode`
  - `png`
  - `os`

### Installation

1. Install the necessary modules using pip if they are not already installed:

    ```sh
    pip install pyqrcode pypng
    ```

2. Save the source code provided in the `http_server_with_qrcode.py` file.

### Running the Server

1. Open a terminal or command prompt.
2. Navigate to the directory where `http_server_with_qrcode.py` is saved.
3. Run the script:

    ```sh
    python http_server_with_qrcode.py
    ```

4. The script will:
    - Change the working directory to your desktop.
    - Start an HTTP server on port 8010.
    - Generate a QR code that links to the server's IP address and port.
    - Open the QR code in your default web browser.

5. Scan the QR code with your mobile device to access the server from the browser.

## Example

When you run the script, you will see output similar to the following:

