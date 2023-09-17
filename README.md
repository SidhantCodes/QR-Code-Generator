# QR Code Generator 

This Node.js script allows you to generate a QR code from a user-provided URL and save it as an image file. It also saves the URL to a text file for reference.

## Prerequisites

Before running this script, ensure you have Node.js installed on your system.

## Installation

1. Clone this repository or download the script file.

2. Open your terminal and navigate to the directory where the script is located.

3. Install the required Node.js modules by running the following command:
```
npm install inquirer qr-image
```


## Usage

1. Run the script using the following command:

```node script.js```

2. You will be prompted to enter a URL. Type in the URL and press Enter.

3. The script will generate a QR code image from the URL and save it as `qrimg.png` in the same directory.

4. It will also save the entered URL to a text file named `logUser.txt`.

5. You will see a "Saved URL successfully" message if the operation is successful.

## Dependencies

- [inquirer](https://www.npmjs.com/package/inquirer): For prompting the user for input.
- [qr-image](https://www.npmjs.com/package/qr-image): For generating QR codes.
- [fs](https://nodejs.org/api/fs.html): For file system operations.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.


