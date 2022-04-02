# Base Conversion and Floating Point Representation
## Due Date: March 8, 2020 at 11:59 PM
--
## Name:                                 <!-- response -->
## GitHub Account:                       <!-- response -->

## Problems:
* For each of the problem, perform the following steps:
  1. Represent the number as a binary (base 2) number
  1. Represent the number as in Scientific Notation (using base 2)
  1. Represent the number in IEEE binary16 format
  1. Represent the number in IEEE binary32 format

### 2# - 11.01 x 2^ 1 0010  (unnormalized exponential form)

  1. Convert to base 2: - 11010000000000000000.0        <!-- response -->

  1. Scientific Notation: 2# - 1.101 x 2^ 10011         <!-- response -->

  1. IEEE Binary16: 
     * x | error | xxxx xxxx xx                         <!-- response -->
     * 15 (bias) + 19 = 34 -> 10 0010 
     * Note that you need 6 bits to represent the exponent, but only have 5 bits are allowed.

  1. IEEE Binary32:
     * x | xxxx xxxx | xxxx xxxx xxxx xxxx xxxx xxx     <!-- response -->
     * 127 (bias)  x + x = xxxx xxxx ->                 


### 2# - 0.00010010 

  1. Convert to base 2: 2# - 0.00010010                 <!-- response -->
  1. Scientific Notation:                               <!-- response -->
  1. IEEE Binary16:
     *                                                  <!-- response -->
     *
  1. IEEE Binary32:
     *                                                  <!-- response -->
     *


### 8#  12.34
  1. Convert to base 2:                                 <!-- response -->
  1. Scientific Notation:                               <!-- response -->
  1. IEEE Binary16:
     *                                                  <!-- response -->
     *
  1. IEEE Binary32:
     *                                                  <!-- response -->
     *

### 16# - 0.0FF
  1. Convert to base 2:                                 <!-- response -->
  1. Scientific Notation:                               <!-- response -->
  1. IEEE Binary16:
     *                                                  <!-- response -->
     *
  1. IEEE Binary32:
     *                                                  <!-- response -->
     *


### 10# 3.14
  1. Convert to base 2:                                 <!-- response -->
  1. Scientific Notation:                               <!-- response -->
  1. IEEE Binary16:
     *                                                  <!-- response -->
     *
  1. IEEE Binary32:
     *                                                  <!-- response -->
     *

## Resources: 
  * [Real Decimal: Conversions](https://docs.google.com/spreadsheets/d/1aMvlfw_rzvYBObT94dX8v_O0EgELHgWrmZgWKmoLY7s/edit#gid=1434558784)
  * [Conversion to Float](https://github.com/COMP122/class-material/blob/main/LectureNotes/format_encodings/Oct_7/Conversion_2Float.md)

