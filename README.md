🔗 Node.js QR Code Generator

This is a simple Command Line Interface (CLI) application built with Node.js. It prompts the user for a URL, then generates a QR code image for that URL and saves both the image and the original URL to local files.

✨ Features

CLI Interaction: Uses the inquirer package to prompt the user for input directly in the terminal.

QR Code Generation: Converts the user-provided text/URL into a standard QR code image using the qr-image package.

File Output: Automatically saves two files to the project directory:

qr_img.png: The generated QR code image.

URL.txt: A text file containing the URL provided by the user.

⚙️ Technologies Used

Node.js: The runtime environment for executing the JavaScript code outside of a web browser.

inquirer: A popular npm package used to create interactive command-line prompts.

qr-image: An npm package dedicated to generating various types of QR code images.

fs (File System): Node's native module used to read and write files (URL.txt and qr_img.png).

🚀 How to Run the Application

Since this is a Node.js CLI application, you need to run it through your terminal.

Install Node.js: Ensure you have the Node.js runtime environment installed on your machine.

Install Dependencies: Navigate to the project folder in your terminal and install the required packages: npm install

Execute the Script: Run the main application file using the node command: node index.js

Enter URL: The terminal will prompt you to enter the URL you wish to convert: ? Type your Url here.

Enter your URL (e.g., https://www.google.com) and press Enter.

The application will confirm successful file creation, and the two output files will appear in the project folder.
