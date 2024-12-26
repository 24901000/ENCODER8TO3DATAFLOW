NAME : B.BARKAVI

REFERENCE NO : 24901000

**EXPERIMENT NO : 5 ENCODER 8 TO 3 DATA FLOW**


**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** 

Quartus prime

**THEORY**

The concept of an encoder in data modeling refers to the transformation of a larger set of inputs into a smaller set of outputs that still preserves as much relevant information as possible. In an 8-to-3 encoder, the idea is to map 8 distinct inputs (or states) into a compressed 3-bit binary representation.

1. Purpose

   
An encoder reduces the number of data lines needed to represent multiple inputs.
It’s commonly used in digital circuits and data compression to efficiently handle large datasets.

2. Basic Operation

   
Each of the 8 inputs corresponds to a unique output represented by a 3-bit binary code.
The encoding process ensures that the information about which input is active is preserved in the compressed 3-bit output.

3. Applications

 
Digital Electronics: Used in priority encoders, multiplexers, and digital signal processors.
Data Compression: Reduces the number of bits for efficient storage and transmission.
Communication Systems: Encodes multiple input signals into fewer output channels.


4. Limitations


Loss of Information: Only one input is active at a time; simultaneous active inputs require priority encoding.
Error Susceptibility: In noisy systems, decoding errors might occur.

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**

 write all the steps invloved 

1. Type the program in Quartus software.
2. Compile and run the program.
3. Generate the RTL schematic and save the logic diagram.
4. Create nodes for inputs and outputs to generate the timing diagram.
5. For different input combinations generate the timing diagram
 

**PROGRAM**

 Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming.
![Screenshot (88)](https://github.com/user-attachments/assets/4c540c87-47eb-4283-8fba-cd60663fabd9)








**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**


![Screenshot (89)](https://github.com/user-attachments/assets/a8e84233-6ee0-48b5-a666-1e6012167d50)



**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**



![Screenshot (90)](https://github.com/user-attachments/assets/9a7027c1-6838-4483-a4d9-79e0335d09bf)


**RESULTS**



The Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables is verified.




