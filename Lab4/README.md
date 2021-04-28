# Lab 4 (Accumulation of Lab2, Lab3, and new lab 4)

# Fundamentals of Lab
Takes the picture capture from lab 2, the encoder from lab3
Use these modules to feed an image to the encoder rle, and then use software to decode
Then feed decoded image to screen 

# Simplified Steps
1) Modify Quartus Hardware configuration
  - Need to include PIOs for communication between RLE and ARM
2) Use Altera Monitor Program for compiling, loading and debugging

# Detailed Steps

1) Modify HW/SW files in lab2 to implement new funcitonality.
2) Use fifo buffer (provided file) and lab3's rle_enc file to quartus project
3) Add eight new PIOs to system
4) Ensure PIOs have correct parameters (width)
5) Export proper signals
6) Connect signals properly
7) Fix errors in system by assigning base addresses
8) Add neccessary wires
9) Instantiate Verilog Modules
10) Add PIO connections to verilog files
11) Compile design
12) Modify C code to finish decoding process
