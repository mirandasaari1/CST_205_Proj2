# CST_205_Proj2
## Steganography 
### Encryption
#### The encryption portion allows a user to choose a photo and a message
#### After choosing the message the message is converted into binary. 
#### From binary the RGB values of the photo are chosen and the least significant bit of 8 pixels are replaced with each number of the
#### letters from the user's message to which the picture is encrypted

### Decryption
### Disclaimer: to decrypt an original, unecnrypted image, is required.
#### The process of decrptying includes breaking up the pixels into RGB values of the two images
#### From there the RGB are converted to decimal, to ascii, to binary and compared binary number by binary number
#### The changed binary numbers are taken and from there converted back to decode the message.
