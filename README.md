Download Link: https://assignmentchef.com/product/solved-ece487-assignment-3-twodimensional-parity-check-bits
<br>
<ol>

 <li>For the following data bits organized in two rows and three columns, please add twodimensional parity-check bits, and give the corresponding codeword. Over the transmission medium, the second bit in the second row is changed from bit ‘0’ to bit ‘1’. Please describe how the receiver will process the received codeword.</li>

</ol>




<ul>

 <li>1 1</li>

 <li>0 1</li>

</ul>




<ol start="2">

 <li>For the Hamming Code discussed in our Lecture 3, show how error correction is performed at the receiver for the following cases. It is required your error detection and correction should be based on the syndrome bits.</li>

 <li>i) Dataword: 0111; error pattern: 0100000  ii) Dataword: 0100;    error pattern: 1000001</li>

</ol>

iii) Dataword: 0011;      error pattern: 1101000

<ol start="3">

 <li>Consider a code (with 4 bits in a dataword and 7 bits in a codeword) using the following three redundant bits:</li>

</ol>

<sub> </sub>r<sub>2</sub> =        a<sub>2</sub> + a<sub>1 </sub>+a<sub>0      </sub>modulo-2                               <sub> </sub>r<sub>1</sub> = a<sub>3</sub>        + a<sub>1</sub> +a<sub>0       </sub>modulo-2                                r<sub>0</sub> = a<sub>3</sub> + a<sub>2</sub> + a<sub>1</sub>        modulo-2

Note that the code could also be called a Hamming Code (not the same as the Hamming Code used in our Lecture 3).

<ul>

 <li>How does the receiver calculate the three syndrome bits?</li>

 <li>The receiver assumes there is at most one bit error in the received codeword. The three-bit syndrome creates eight different bit patterns (“000” to “111”). For each bit pattern, please indicate which bit (among the seven bits in the received codeword) the receiver considers corrupted.</li>

</ul>

<table width="566">

 <tbody>

  <tr>

   <td width="78">Syndrome S2S1S0</td>

   <td width="61">000</td>

   <td width="61">001</td>

   <td width="61">010</td>

   <td width="61">011</td>

   <td width="61">100</td>

   <td width="61">101</td>

   <td width="61">110</td>

   <td width="61">111</td>

  </tr>

  <tr>

   <td width="78">Corruptedbit</td>

   <td width="61"> </td>

   <td width="61"> </td>

   <td width="61"> </td>

   <td width="61"> </td>

   <td width="61"> </td>

   <td width="61"> </td>

   <td width="61"> </td>

   <td width="61"> </td>

  </tr>

 </tbody>

</table>




<ol start="4">

 <li>For the CRC code system with divisor “1011” discussed in Lecture 3, Denote the 4-bit dataword at the sender as a<sub>3</sub>a<sub>2</sub>a<sub>1</sub>a<sub>0</sub>, and the 7-bit codeword at the sender as a<sub>3</sub>a<sub>2</sub>a<sub>1</sub>a<sub>0</sub>r<sub>2</sub>r<sub>1</sub>r<sub>0</sub>. (i) Give the codeword for dataword “1101”.  You are required to use division to get the codeword.</li>

</ol>

(ii) For the codeword in (i), if bits a<sub>2, </sub>a<sub>1, </sub>and a<sub>0</sub> are corrupted during the transmission, give the syndrome bits at the receiver. Will the receiver accept the received codeword?   (iii) Repeat question (ii) if bits a<sub>1</sub>, r<sub>2</sub> and r<sub>1</sub> are corrupted during the transmission.


