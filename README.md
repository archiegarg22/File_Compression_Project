# File Compression Project using Huffman Coding in C++

# Introduction
The project entails developing compression and decompression utilities utilizing Huffman Coding, where character encoding varies inversely with frequency—a higher frequency corresponds to a shorter code. The objective is to efficiently compress data by assigning optimal bit representations to each character based on their occurrence rates. This approach ensures that frequently appearing characters are represented compactly, optimizing storage and transmission efficiency.

# Implementation
The program has been implemented in C++ language with the goal of optimizing storage efficiency through Huffman Coding, where frequent characters are assigned concise codes. This approach aims to minimize expected storage requirements by prioritizing shorter bit representations for commonly encountered characters.

# Compression:
-> Input the data for compression.

-> Record the frequency distribution of all characters within the input.

-> Constuct a min priority queue with respect to the character frequencies.

-> Construct the Huffman Tree using the priority queue.

-> Generate an encoding table that maps each character to its respective Huffman code.

-> Compress the input data utilizing the generated encoding table.

 *The codes are stored as bits and each character is provided a prefix code which is a string of bits.*

![compression](https://github.com/archiegarg22/File_Compression_Project/assets/155153189/5b21673d-e073-41fd-9843-25b2d3b51c8d)


# Decompression:
-> Open the encoded file that contains the compressed data.

-> Utilize the encoded table, which maps characters to their respective Huffman codes.

-> Reconstruct the Huffman Tree from the encoded table.

-> Decode the compressed data.

-> Save the decoded data to the desired file location.

![depression](https://github.com/archiegarg22/File_Compression_Project/assets/155153189/42c7665b-4946-4a80-b270-7bcba24a76c7)


# Finding Compression Efficiency:
A compression yielding between _% to _% reduction in size compared to the original input file has been achieved.

![efficiency](https://github.com/archiegarg22/File_Compression_Project/assets/155153189/29be111a-7b71-402e-b080-98343eb61902)


# Output:

