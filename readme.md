# WiFi Barcode Generator

This is a simple web application that generates a barcode for WiFi credentials, allowing users to easily share WiFi information by scanning the barcode. The app takes the WiFi network name (SSID) and password as input, and generates a barcode that can be scanned by a mobile device or a barcode reader.

## Features

- Generate a barcode for WiFi credentials (SSID, password).
- Barcode contains the WiFi network name and password in a specific format.
- User-friendly and minimal design.
- Works across different devices and browsers.

## Technologies Used

- **HTML**: For creating the structure and layout of the web page.
- **CSS**: For styling and responsive design.
- **JavaScript**: For barcode generation and handling user inputs.
- **JsBarcode**: A JavaScript library to generate the barcode from input data.

## Installation

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/Guru9696/WiFi-Barcode-Generator.git
   \`\`\`

2. Open the \`index.html\` file in your browser.

3. Ensure you have an internet connection to load the external JsBarcode library.

## Usage

1. Enter your WiFi network SSID (network name) and password in the provided input fields.
2. Click on the "Generate Barcode" button.
3. The barcode will be generated below the form.
4. Scan the barcode with any barcode reader or mobile device to retrieve the WiFi credentials.

### WiFi Format
The WiFi information will be encoded in the following format:
\`\`\`
WIFI:T:WPA;S:<SSID>;P:<PASSWORD>;;
\`\`\`
Where:
- \`T\` is the security type (WPA, WPA2, etc.)
- \`S\` is the SSID (WiFi network name)
- \`P\` is the WiFi password

## Example

### Input:
- SSID: MyWiFiNetwork
- Password: SuperSecretPassword

### Output (generated barcode):
- The barcode will represent the following string:
  \`\`\`
  WIFI:T:WPA;S:MyWiFiNetwork;P:SuperSecretPassword;;
  \`\`\`



## Acknowledgments

- **JsBarcode**: Barcode generation library used in this project.
- **Open Source Community**: For providing libraries and tools that make building web applications easier.

---

Feel free to reach out if you have any questions or need further assistance!

## Contact
For any inquiries or support, please contact [Your Name] at [your-email@example.com].


