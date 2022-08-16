# Design-and-implement-an-error-detection-in-CN
Design and implement an error detection module which has four schemes namely LRC, VRC, Checksum and CRC. 
The Sender program would accept the name of a test file (contains a sequence of 0,1) from the command line. 
Then it will prepare the data frame (decide the size of the frame) from the input.
Based on the schemes, codeword will be prepared. 
Sender will send the codeword to the Receiver. 
Receiver will extract the dataword from codeword and show if there is any error detected.
Testing the same program to produce a PASS/FAIL result for following cases.
(a) Error is detected by all four schemes. Use a suitable CRC polynomial.
(b)  Error is detected by checksum but not by CRC.
(c)  Error is detected by VRC but not by CRC.
