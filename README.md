# steganography-meme-builder
This tool hides secret messages in images using steganography. The message is embedded in the least significant bits of the image pixels, making it virtually undetectable to the naked eye.
To hide a message: Upload an image, enter your text, and click "Hide Text"
To extract a message: Upload an image with hidden text and click "Extract Text"
Higher bit modes allow more text but may slightly alter the image
For best results, use PNG images (JPEG compression may corrupt hidden data)
Steganography Meme Builder © 2025 | All images are processed locally in your browser
Key Improvements:
Modern UI/UX:

Clean, responsive design with card-based layout

Drag and drop file upload

Progress indicators for operations

Better status messaging

Enhanced Functionality:

Configurable LSB depth (1, 2, or 4 bits)

Channel selection (RGB, Red, Green, or Blue)

Basic encryption options (XOR)

Capacity calculator based on image size and settings

Performance Improvements:

Image resizing for large files

Progress reporting during operations

Better memory management

Error Handling:

Comprehensive error messages

Input validation

Try-catch blocks for operations

Additional Features:

Reset functionality

Help section explaining how it works

File name display

Visual feedback during operations

Accessibility:

Better contrast

Clear labels

Responsive design for mobile devices
