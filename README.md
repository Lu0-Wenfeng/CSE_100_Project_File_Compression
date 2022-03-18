# Project_CSE_100_Project_File_Compression
The code is made private because of the Academic Integrity.

Send me a request if you want to take a look:)

## Project Overview

In this project, I implemented two programs: `compress.cpp` and `uncompress.cpp`. The usage should be as follows:
```c++
./compress <original_file> <compressed_file>
./uncompress <compressed_file> <uncompressed_file>
```

The `compress` program will take as input an arbitrary file (`original_file`) and will use Huffman Compression to create a compressed version of the file (`compressed_file`):

1. Construct a Huffman code for the contents of `original_file`
2. Use the constructed Huffman code to encode `original_file`
3. Write the results (with a header to allow for uncompression) to `compressed_file`

The `uncompress` program will then take as input a compressed file created by your `compress` program (`compressed_file`) and will uncompress the file (`uncompressed_file`):

1. Construct a Huffman code by reading the header of `compressed_file`
2. Use the constructed Huffman code to decode `compressed_file`
3. Write the results to `uncompressed_file`

Two programs (`refcompress` and `refuncompress`) are provided, which are a reference solution implementation of this Project. **You can use them to help guide you. Note that the reference binaries were compiled to run on Ed, so if you attempt to run them on a different architecture, they will most likely not work.**
