🖼️ LSB Image Steganography using C

A C-based implementation of Least Significant Bit (LSB) steganography to hide and extract secret data inside BMP image files using bitwise operations and file handling.

🚀 Features

- Encode secret text into BMP image

- Decode hidden data from encoded image

- Magic key authentication for secure extraction

- Uses low-level file operations (fread, fwrite)

- Capacity validation before encoding

- Preserves original image header

🧠 Working Principle

- Secret data is converted into binary form

- Least Significant Bits of image pixel data are modified

- Only minimal bit-level changes are made

- Image visually appears unchanged

📝 Usage

Encode
    
    
    ./stego -e input.bmp secret.txt output.bmp


Decode


    ./stego -d output.bmp



📚 Concepts Used

- File I/O in C

- Bitwise operations

- BMP file structure handling

- Data encoding and decoding

- Basic key-based validation
