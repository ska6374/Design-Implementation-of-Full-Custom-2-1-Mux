# Design Implementation of Full Custom 2:1 Mux

<h2>I. Introduction :</h2>
<dr>The 2×1 is a fundamental circuit which is also known 2-to-1 multiplexer that are used to choose one signal from two inputs and transmits it to the output. The 2×1 mux has two input lines, one output line, and a single selection line. It has various applications in digital systems such as in microprocessor it is used to select between two different data sources or between two different instructions.<dr>
<br>
  <br>
<h2>II. Block Diagram of 2:1 Multiplexer with Truth Table :</h2>
Given Below is the Block Diagram and Truth Table of 2:1 Mux. In this Block Diagram where I0 and I1 are the input lines ,Y is the output line and S0 is a single select line.

![Screenshot (136)](https://github.com/user-attachments/assets/d5a33469-e12e-4088-b75f-9714cf996d9e)


The output of the 2×1 Mux will depend on the selection line S0,

When S is 0(low), the I0 is selected
when S0 is 1(High), I1 is selected


Logical Expression of 2×1 Mux

![Screenshot (138)](https://github.com/user-attachments/assets/c661971d-8658-4c23-a1d0-6e77eebca7fd)
<br>
<br>
<h2>III. Advantages of MUX</h2>

1. Efficiency: The Mux has good efficiency in routing multiple input signals to a single out signal based on control signals.<dr><br>
2. Optimization: The Mux helps to conserve resources such as wires, pins and integrated circuit(IC).<dr><br>
3. Different Implementation: The Mux can be used to implement different digital logic functions such AND,OR etc.<dr><br>
4. Flexibility: Mux can be easily configure according to the requirements and accommodate different data sources, enhancing system versatility.<dr><br>
<br>
<br>
<H2>IV. Applications of MUX</H2>

1. Data Routing: The Mux is used for data routing in the digital system where they select one of the several data lines and re-route it the output.<dr>
2. Data Selection: The Mux is used for data selection where they select data source according to the select lines.<dr><br>
3. Analog-to-Digital Conversion: The Mux are used in ADC to select different analog input channels.<dr><br>
4. Address Decoding: The Mux are used in Microprocessors or memory for address decoding.<dr><br>
5. Logic Function Implementation: Muxes can be used to implement various logic functions.<dr><br>
<br>
<br>

<H2>V. Tools Used :</H2>

• Schematic: Cadence Virtuoso Schematic XL<dr><br>
• Simulation: Cadence Virtuoso - ADE L<dr><br>
• Layout: Cadence Virtuoso - Layout XL<dr><br>
• Technology: gpdk180<dr><br>

<br>
<br>
<h2>VI. Schematic</h2>

<br>

![Screenshot](https://github.com/user-attachments/assets/b657e080-480b-4f85-beda-7911e1b253c9)
<BR>
<BR>
<H2>VII. Symbol Genarate</H2>

<br>

![Screenshot-2](https://github.com/user-attachments/assets/b1ba4b9e-96ae-49c0-a8c8-852fd22e2ed8)
<br>
<br>
<h2>VIII. Output Waveform</h2>
<br>


![Screenshot-4](https://github.com/user-attachments/assets/880ddd17-204b-4e5d-b2d0-fef5b27522c1)
<br>
<br>
<h2>IX. Layout :</h2>
<br>

![image](https://github.com/user-attachments/assets/6793a6c7-9f25-4097-9037-7b8593f2a254)










