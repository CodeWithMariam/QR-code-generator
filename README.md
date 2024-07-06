# QR Code Generator

This is a simple web-based QR code generator that allows users to create QR codes from text or URLs. The generated QR codes are displayed on the webpage, and the application uses an external API to generate the codes.

## Features

- Generate QR codes from user-inputted text or URLs
- Display generated QR codes on the webpage
- Simple and user-friendly interface

## Technologies Used

- HTML
- CSS
- JavaScript
- [QR Code API](https://goqr.me/api/)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/CodeWithMariam/QR-code-generator.git
    ```
2. Open `index.html` in your browser.

## Usage

1. Enter the text or URL you want to encode in the input box.
2. Click the "Generate QR Code" button.
3. The generated QR code will be displayed on the page.

## Code Explanation

- The `imgBox` element is used to hold the QR code image.
- The `qrImage` element displays the generated QR code.
- The `qrText` element is the input field where the user enters text or a URL.
- The `generateQR` function generates the QR code using the [QR Code API](https://goqr.me/api/) and updates the `qrImage` element's `src` attribute to display the generated code.
- If the input field is empty, an error class is added to the input field for 1 second to indicate an error.

## Future Improvements

- Add options to customize the size and color of the QR code.
- Allow users to download the generated QR code.
- Improve error handling and user feedback.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Related Links

- [QR Code API](https://goqr.me/api/)
- [How to Generate QR Codes with JavaScript](https://www.sitepoint.com/generate-qr-codes-with-javascript/)
- [Understanding QR Codes](https://www.qrcode.com/en/about/)
