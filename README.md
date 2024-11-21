
# QR Code Generator

## Overview

This **QR Code Generator** allows users to input a text or URL, which is then converted into a downloadable QR code image. The generated QR code is displayed below the input box, and users can also download the image to their devices.

## Features

- **Generate QR Codes**: Converts user-provided text or URL into a QR code.
- **Preview QR Code**: Displays the generated QR code before download.
- **Download QR Code**: Allows users to download the generated QR code image in PNG format.

## Technologies Used

- **HTML**: For the structure of the webpage.
- **CSS**: For styling and design of the webpage.
- **JavaScript**: To handle the QR code generation and image download functionality.
- **QR Code API**: The app uses an external API (QR Server) to generate QR codes from the input data.

## How to Use

1. Open the `index.html` file in your browser.
2. In the input box, enter the text or URL you want to convert into a QR code.
3. Click the **"Generate QR Code"** button.
4. The QR code will appear below the input box.
5. To download the QR code, click the **"Download QR Code"** button. The image will be saved as a PNG file on your device.

## How to Run Locally

1. Clone or download the project to your local machine.
   ```bash
   git clone https://github.com/ShivaanjayNarula/qr-code-generator.git
   ```
2. Navigate to the project folder.
   ```bash
   cd qr-code-generator
   ```
3. Open `index.html` in a web browser to start using the application.

## Folder Structure

```
qr-code-generator/
│
├── index.html         # The main HTML file
├── style.css          # Styles for the webpage
└── README.md          # Project README file
```

## Contribution

Feel free to fork the repository and submit pull requests with improvements or new features!

## License

This project is open-source and available under the [MIT License](LICENSE).
