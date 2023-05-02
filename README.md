Download Link: https://assignmentchef.com/product/solved-comp3353-project-2
<br>



<ul>

 <li>Get you familiar with Microsoft Macro Assembler (MASM) on Visual Studio.</li>

 <li>Setting up an assembly program.</li>

 <li>Defining and accessing Arrays.</li>

 <li>Dealing with Registers and instructions.</li>

 <li>Debugging and running your assembly code.</li>

</ul>

<strong>Requirements: </strong>

<ul>

 <li>Read the design section and write a program. Submit source file (.asm) to Canvas.</li>

 <li>Show your work to get full credit. ZERO point without steps for a result.</li>

 <li>Please start early. ZERO point for late submission. After the 11:59pm on the due day, you cannot submit your assignment anymore.</li>

 <li>Check deliverables section below. ZERO point for hand-written or scanned homework.</li>

</ul>

<strong>Deliverables: </strong>

<ul>

 <li>Save your source of assembly program as a .asm document.</li>

 <li>Name document as a “Firstname_Lastname.asm”.</li>

 <li>Submit your “Firstname_Lastname.asm” through the Canvas system. You do not need to submit hard copies.</li>

</ul>

<strong>Rebuttal period: </strong>

<ul>

 <li>You will be given a period of 3 business days to read and respond to the comments and grades of your homework or project assignment. The TA may use this opportunity to address any concern and question you have. The TA also may ask for additional information from you regarding your homework or project.</li>

</ul>

<strong>Design: </strong>

The objective of this assignment is to create a program that will read a value from an array, add another value to this, and save the sum of those two values into a specific register.

(20 points) Create a BYTE array with the label ‘input’. ‘input’ should have eight elements. You should place values 1,2,3,4,5,6,7,8 in each of the elements of this array.

(20 points) Create a BYTE variable with the label ‘shift’. ‘shift’ should hold a single value 2.

(20 points) Set the values of the EAX, EBX, ECX, and EDX to 0. You then sum the value of this variable with each of the individual values in the array ‘input’. The program should read each of the values from the array ‘input’ one at a time and add the value ‘shift’ to it.

The sum should be stored in the “correct” register:

(5 points) The first sums should be in high position of the AX register.

(5 points) The second sums should be in low position of the AX register.

(5 points) The third sums should be in high position of BX register.

(5 points) The fourth sums should be in low position of BX register.

(5 points) The fifth sums should be in high position of CX register.

(5 points) The sixth sums should be in low position of CX register.

(5 points) The seventh sums should be in high position of the DX register.

(5 points) The eighth sums should be in low position of the DX register.