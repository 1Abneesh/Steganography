# Steganography
Steganography is hiding (embedding) data (file) in an image using techniques that ensure that the image doesn't get corrupted.
The objective of this Python project is to hide the message within the image and then decode the image.It uses openCV module for encoding and decoding the image.
In this we are using LSB based image steganography.Least Significant Bit (LSB) is a technique in which the last bit of each pixel is modified and replaced with the secret message’s data bit.
since we are using lsb of an image so their is not much difference after embedding it with secret message.
