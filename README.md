# Minor project
Code on "encrypt -> encode -> decode -> decrypt" of a text file using 'AES' and 'Huffman encryption'.

AES:
Advanced Encryption Standard (AES) is a specification for the encryption of electronic data established by the U.S National Institute of Standards and Technology (NIST) in 2001. AES is widely used today as it is a much stronger than DES and triple DES despite being harder to implement.
Points to remember
1- AES is a block cipher.
2- The key size can be 128/192/256 bits.
3- Encrypts data in blocks of 128 bits each.

AES Decryption:
The stages in the rounds can be easily undone as these stages have an opposite to it which when performed reverts the changes.Each 128 blocks goes through the 10,12 or 14 rounds depending on the key size.
The decryption process is the encryption process done in reverse

To know more about AES please visit - https://www.geeksforgeeks.org/advanced-encryption-standard-aes/

Hoffman Coding:
Huffman coding is a lossless data compression algorithm. The idea is to assign variable-length codes to input characters, lengths of the assigned codes are based on the frequencies of corresponding characters. The most frequent character gets the smallest code and the least frequent character gets the largest code.
The variable-length codes assigned to input characters are Prefix Codes, means the codes (bit sequences) are assigned in such a way that the code assigned to one character is not the prefix of code assigned to any other character. This is how Huffman Coding makes sure that there is no ambiguity when decoding the generated bitstream.

To know more  about Hoffman Coding please visit - https://www.geeksforgeeks.org/huffman-coding-greedy-algo-3/?ref=lbp
and for decoding part - https://www.geeksforgeeks.org/huffman-decoding/

How Run code:-
1- Download all the files in the repository
2- Use ide to run the code in order of -
    1- encrypt.cpp
    2- encode.cpp
    3- decode.cpp
    4- decrypt.cpp
    
On runing encrypt.cpp it create message.aes file then encode.cpp will encode message.aes into message.aes.huf and we get the encrypted and encoded file.
as for decoding and decryption part we have first run decode.cpp wich decode the message.aes.huf file into message.aes after that we can just run decrypt.cpp to decrypt and we get the original file.
