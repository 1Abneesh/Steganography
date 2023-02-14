# Steganography Project

Steganography is the art of hiding data in plain sight. This Python project aims to hide a message within an image using techniques that ensure that the image remains intact. The objective of this project is to embed the message within the image and then decode it.

## Features
The objective of this Python project is to hide a message within an image and then decode the image using techniques that ensure the image doesn't get corrupted. The project uses the openCV module for encoding and decoding the image and is based on the Least Significant Bit (LSB) image steganography technique.

## Usage
->Clone the repository to your local machine:
`git clone https://github.com/<your-username>/steganography-project.git`

-> Navigate to the directory:
`cd steganography-project`

-> Run the application using the following command:
`python app.py`

## Tools Used
- openCV: Used for encoding and decoding the image
- Least Significant Bit (LSB) image steganography: The technique used in this project to embed the secret message into the image by modifying the last bit of each pixel.

## Methodology
The project uses LSB based image steganography to embed the secret message into the image. In this technique, the last bit of each pixel is replaced with the data bit of the secret message. This results in minimal differences in the image after embedding the secret message, making it difficult to detect.

## Screenshot
<p align="center">
  <img src="1.png">
</p>

<p align="center">
  <img src="2.png">
</p>

<p align="center">
  <img src="3.png">
</p>

## Conclusion
This project demonstrates the use of image steganography to hide data in plain sight. The use of LSB based image steganography helps to ensure that the image remains intact after embedding the secret message, making it a secure method of transmitting data.
