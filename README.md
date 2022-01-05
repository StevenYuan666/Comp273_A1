# Circuit of Seven Segment Decoder Circuit
## Introduction
A seven segment decoder is typically used to determine which light emit- ting diodes in a seven segment display should illuminate to display a digit specified in binary coded decimal.

Logisim-evolution includes such a seven segment display that you will use in this question. The decoder takes four binary bits as the input, which we label in order from most significant bit to least significant bit, A3 A2 A1 A0. The decoder produces as output a pattern of 7 bits, S6 S5 S4 S3 S2 S1 S0, which specifies which segments should illuminate. The figure on the right shows the relationship between the pins and the corresponding segments of the display. Note that there is an 8th pin, S7, which controls the decimal point.

![image](https://user-images.githubusercontent.com/68981504/148277162-a89ab3ea-505b-46fe-80ee-9197c874e5bf.png)

A possible combination is as following:

![image](https://user-images.githubusercontent.com/68981504/148277212-0beecce2-cbbb-40a3-af3a-d8fb6cf964cd.png)

## Overall Design

![image](https://user-images.githubusercontent.com/68981504/148277424-686b43c6-ea4c-4a63-a203-4f4409fcd200.png)

