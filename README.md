# DATA-COMPRESSION-TOOL-
*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: PRIYANSHI SHARMA

*INTERN ID*: CT06DH407

*DOMAIN*: C PROGRAMMING INTERN

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION* : For the final task of my internship, I was assigned a very practical and exciting project—building a file compression and decompression program using the Run-Length Encoding (RLE) algorithm in the C programming language. This task not only challenged my logical thinking and implementation skills but also allowed me to understand how data compression works at a fundamental level.

The goal was to take an input text file (input.txt) that contains a sequence of repeating characters and compress it into a smaller file (compressed.txt) using RLE. Then, using that compressed file, the program had to decompress it back into its original form (decompressed.txt). This two-part process demonstrated the full cycle of how data can be compacted and restored without any loss.

The Run-Length Encoding (RLE) algorithm is a basic yet powerful compression method where consecutive occurrences of the same character are replaced with a single character followed by the number of repetitions. For instance, the string AAAABBBCCDAA would be compressed to A4B3C2D1A2. This algorithm is especially useful when the input data contains many repeated characters, making it ideal for compressing plain text and basic image formats.

To complete this task, I first created a sample input file containing a sequence of characters with repetition. Then, I wrote a C program that opens this file, reads it character by character, and counts the number of consecutive occurrences of each character. This information is written into the compressed file. Next, I implemented a decompression logic that reads the compressed file, identifies each character and its count, and reconstructs the original data by printing each character the appropriate number of times. This output is stored in decompressed.txt.

The challenge here was not just in understanding the algorithm but also in managing file handling, character operations, and memory efficiently using C. Since C doesn’t offer as many built-in high-level file processing functions as modern languages, I had to be extra cautious with how I opened, read, wrote, and closed the files. I also had to test my code with different types of inputs to ensure that both compression and decompression worked correctly in every scenario.

By the end of this task, I had a fully functional mini file compression tool written entirely in C. It may be simple, but it gave me an immense sense of accomplishment. More importantly, I now feel more confident in working with file I/O, string operations, and basic algorithm design in C. This task pushed me to apply everything I’ve learned throughout the internship, and I’m really proud to say that I completed it independently with proper understanding.

This task not only marked the end of my internship but also symbolized how much I’ve grown technically in a short span. It was a perfect finale to an enriching journey.

*OUTPUT*
