# CodingProblem1

Problem: Write best pratice in javasript to calculate the check digit of an ISBN13 barcode.
The algorithm is:

Step:1.Take each digit, from left to right and multiply them alternatively by 1 and 3
Step:2. Sum those numbers
Step:3. Take mod 10 of the summed figure
Step:4. Subtract 10 and if the end number is 10, make it 0.

Example for 978014300723
 
 sum =  (9×1) + (7×3) + (8×1) + (0×3) + (1×1) + (4×3) + (3×1) + (0×3) + (0×1) + (7×3) + (2×1) + (3×3)
 sum=  86
 node= 86 mod 10 = 6
 check digit = 10 - 6 = 4
  isbn= 9780143007234
