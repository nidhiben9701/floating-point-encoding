# Base Conversion and Floating Point Representation

## Name: Steven Fitzgerald                               <!-- answer -->
## Due Date:
---
## Problems:
### 2#  - 11.01 x 2^ 1 0010  (unnormalized exponential form)

  1. Convert to base 2:
     * - 11010000000000000000.0                      <!-- answer -->

  1. Scientific Notation:
     * -  1.101 x 2^ 10011 (19)                      <!-- answer -->

  1. IEEE Binary16: 
     * 1 | 1 0010 | 1010 0000 00                     <!-- answer -->
     * 15 (bias) + 19 = 34 -> 1 0010 

  1. IEEE Binary32:
     * 1 | 1001 0010 | 1101 0000 0000 0000 0000 000  <!-- answer -->
     * 127 (bias) + 19 = 146 -> 1001 0010 

### 2# - 0.00010010 

  1. Convert to base 2: 2# - 0.00010010 
     * - 0.00010010                                  <!-- answer -->

  1. Scientific Notation: 
     * - 1.0010 x 2^ -100 (-4)                       <!-- answer -->

  1. IEEE Binary16:
     * 1 | 0 1011 | 0010 0000 00                     <!-- answer -->
     * 15 (bias) + -4 = 11 -> 1011

  1. IEEE Binary32:
     * 1 | 111 1011 | 0010 0000 0000 0000 0000 000   <!-- answer -->
     * 127 (bias) + -4 = 123 -> 111 1011


### 8#  12.34

  1. Convert to base 2:
     * 2# 001 010.011 100                            <!-- answer -->

  1. Scientific Notation:
     * 1.010 011 100 x 2^ 11 (3)                     <!-- answer --> 

  1. IEEE Binary16:
     * 1 | 1 0010 | 0100 1110 00                     <!-- answer --> 
     * 15 (bias) + 3 = 18 -> 1 0010

  1. IEEE Binary32:
     * 1 | 0111 1100 | 0100 1110 0000 0000 0000 000  <!-- answer -->
     * 127 (bias) + 3 = 124 -> 0111 1100


### 16# - 0.0FF

  1. Convert to base 2:
     * - 0000.0000 1111 1111                         <!-- answer -->

  1. Scientific Notation:
     * - 1.111 1111 x 2^ - 101 (-5)                  <!-- answer --> 

  1. IEEE Binary16:
     * 1 | 0 1010 | 1111 1110 00                     <!-- answer -->
     * 15 (bias) + -5 = 10 -> 0 1010

  1. IEEE Binary32:
     * 1 | 0111 1010 | 1111 1110 0000 0000 0000 00   <!-- answer -->
     * 127 (bias) + -5 = 122 -> 0111 1010  


### 10# 3.14
  1. Convert to base 2:
     * 11.00100011110101110000101000111101           <!-- answer -->

  1. Scientific Notation:
     * 1.100100011110101110000101000111101 x 2^ 1    <!-- answer --> 

  1. IEEE Binary16:
     * 1 | 1 0000 | 1001 0001 11                     <!-- answer -->
     * 15 (bias) + 1 = 16 -> 1 0000

  1. IEEE Binary32:
     * 1 | 1000 0000 | 1001 0001 1110 1011 1000 01   <!-- answer -->
     * 127 (bias) + 1 = 128 -> 1000 0000

