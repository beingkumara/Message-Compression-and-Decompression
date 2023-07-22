# Message-Compression-and-Decompression



Description:
The "Huffman Coding Implementation" project is a C++ program that demonstrates the concept of Huffman coding, a popular data compression technique used to reduce the size of messages or data files efficiently. Huffman coding assigns variable-length codes to characters based on their frequencies in the input message, allowing more frequent characters to have shorter codes and less frequent characters to have longer codes. This approach minimizes the overall space required to represent the message.

The project consists of the following key components:

1. huffman_tree Class: A class representing a binary tree node used to build the Huffman tree. Each node contains information about the character, its frequency in the input message, and pointers to its left and right child nodes.

2. PriorityQueue: A data structure implemented as a binary heap that prioritizes nodes based on their frequencies. The heap is used to construct the Huffman tree efficiently.

3. Encoding and Decoding Functions: The project includes functions for encoding an input message using the constructed Huffman tree and decoding an encoded message back to its original form.

4. Frequency Calculation: A function to calculate the frequencies of each character in the input message, which serves as the basis for constructing the Huffman tree and generating the encoding table.

5. Output Files: The program writes the Huffman encoding table (character-frequency-code) to "huffmanTable.txt" and the encoded message to "encoded_data.txt." Additionally, the decoded message is written to "target_message.txt."

By implementing this project, the program showcases the power of Huffman coding in reducing the size of data efficiently, which can be particularly useful in scenarios where data storage or transmission bandwidth is limited. The project also demonstrates a good understanding of data structures such as binary trees and priority queues and showcases programming skills in C++. Adding this project to your resume under the "Projects" section will demonstrate your ability to work on data compression algorithms and your proficiency in C++ programming.
