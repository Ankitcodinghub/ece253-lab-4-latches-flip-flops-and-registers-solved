# ece253-lab-4-latches-flip-flops-and-registers-solved
**TO GET THIS SOLUTION VISIT:** [ECE253 Lab 4-Latches, Flip-flops, and Registers Solved](https://www.ankitcodinghub.com/product/ece253-laboratory-exercise-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109994&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE253 Lab 4-Latches, Flip-flops, and Registers Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Latches, Flip-flops, and Registers

The purpose of this exercise is to investigate the fundamental synchronous logic elements:

latches, flip-flops, and registers.

1 Work Flow

For Part I you will use logisim or the breadboard in lab to build and simulate the circuit.

2 Part I

Figure 1 shows the circuit for a gated D latch (textbook Section 5.3). In this part, you will build the gated D latch using the logisim simulator. Or if you wish, you can also do this using the breadboard you used in Lab 1.

2.1 What to Do

Perform the following steps:

There are two options. If you liked playing with the chips in Lab 1, you can do it again for this part, otherwise, you should play with the circuit using logisim.

1. Construct the circuit.

(a) If you are in the lab:

i. In your lab book, draw a schematic of the gated D latch using interconnected7400-series chips. Recall from Lab 1 what a gate-level schematic looks like. ii. Build the gated D latch using the chips and breadboard. Use switches to control the clock and D input. Use lights to make Qa and Qb visible. Don’t forget to hook up the power and ground on all of your chips!

(b) If you are doing simulation with logisim

i. Using the logisim Gates library build the circuit shown in Figure 1. Note that when you select the NAND gate tool, you can first change the number of inputs to 2.

2. Study the behaviour of the latch for different D and Clk settings. Observe Q when Clk is set high and you change D several times. Then observe Q when Clk is set low and you change D several times. How do you set Q high? How do you set Q low?

3. What are all the cases you need to show that your D latch is working correctly?

3 Part II

In modern digital circuit design, latches are rarely used, and only in very special circumstances. The most common storage element today is the edge-triggered D flip flop. One way to build an edge-triggered D flip flop is to connect two D latches in series with the two D latches using opposite edges of the clock. This is called a primary-secondary flip flop (textbook Section 5.4.1). The output of the primary-secondary flip flop changes on a clock edge, unlike the latch, which changes according to the level of the clock. For a positive edge-triggered flip flop, the output changes when the clock edge rises. The Verilog code for a positive edge-triggered flip flop is shown in Figure 2 (textbook Section A.14.2, A.14.3). This flip flop also has an active-low, synchronous reset, meaning that the reset only happens when Reset b = 0 on the rising clock edge. If q is declared as reg q, then you get a single flip flop. If q is declared as reg[7:0] q, then you get eight parallel flip flops, which is called an 8-bit register. Of course, d should have the same width as q.

Starting with the circuit you built for Lab 3 Part III, build an ALU with the eight operations as shown in the pseudo-code in Figure 3. Pay attention and note that the operations of the

always @(posedge Clock) begin // triggered every time clock rises

if (Reset b == 1’b0) // when Reset b is 0 (note this is tested on every rising clock edge)

q &lt;= 0; // q is set to 0. Note that the assignment uses &lt;=

else // when Reset b is not 0

q &lt;= d; // value of d passes through to output q

end

Figure 2: Verilog for a positive edge-triggered flip flop with active-low, synchronous reset.

always @(*) // declare always block begin case (Function) // start case statement

0: A + B using the adder from Part II of Lab 3

1: A + B using the Verilog ‘+’ operator

2: Sign extension of B to 8 bits

3: Output 8’b00000001 if at least 1 of the 8 bits in the two inputs is 1 using a single OR operation

4: Output 8’b00000001 if all of the 8 bits in the two inputs are 1 using a single AND operation

5: Left shift B by A bits using the Verilog shift operator

6: A × B using the Verilog ‘*’ operator

7: Hold current value in the Register, i.e., the Register value does not change default: … // default case endcase end

Figure 3: Pseudo-code for ALU.

3.1 What to Do

The top-level module of your design should have the following signature declaration:

module part2(Clock, Reset b, Data, Function, ALUout);

Figure 4: Simple ALU with register circuit for Part II.

1. Draw a schematic showing your code structure with all wires, inputs and outputslabeled.

2. After drawing your schematic, write the Verilog code that corresponds to your schematic.Your Verilog code should use the same names for the wires and instances as shown in your schematic. Use the code in Figure 2 as the model for your register code.

3. Simulate your ALU with ModelSim to satisfy yourself that your circuit is working.Be prepared to justify that your test cases are enough to give confidence that your circuit is working. When you are satisfied with your simulations, you can submit to the Automarker.

4. Create a new Quartus project for your circuit. You will need a top-level module to makeconnections from the instantiation of your part2 module to the switches, keys, LEDs and HEX displays of the DE1-SoC board. Connect the Data input to switches SW3−0. Connect KEY0 to the Clock input for the register, SW9 to Reset b and use KEY3−1 for the ALU Function inputs. Display ALUout on LEDR7−0; have HEX0 display the value of Data and set HEX1, HEX2 and HEX3 to 0. HEX4 and HEX5 should display the least-significant and most-significant four bits of ALUout respectively.

5. Compile the project to generate a bitstream to make sure your code can at least besynthesized.

6. If you have a board, download the compiled circuit into the FPGA chip. Test thefunctionality of the circuit by toggling the various inputs and observing the outputs.

Figure 5: Sub-circuit for Part III.

7. If you do not have a board, you can use fake fpga to test that your circuit behaves as expected.

4 Part III

Figure 5 shows a positive edge-triggered flip-flop with several multiplexers. In this part of the lab, you will use eight instances of the circuit in Figure 5 to design a left/right 8-bit rotating register with parallel load shown in Figure 6.

A rotating register uses the concept of shifting bits (text Section 5.8, A.14.5) in the register. When bits are shifted in a register, it means that the bits are copied to the next flip flop on the left or the right. For example, to shift the bits left, each flip flop loads the value of the flip flop to its right when the clock edge occurs. The term rotating comes from how the bits at the ends of the register are handled. In the left-shift example, the flip flop at the right end of the register has no right neighbour. One option is to load a zero, but for rotation we load the value of the flip flop at the left end of the register. The behaviour is as if the register were really a ring because the left and right ends are connected.

The LoadLeft input of all eight instances of the circuit in Figure 5 should be tied to the single rotating register input RotateRight because when you want to rotate the bits right, you have to load the bit to the left. The loadn input of all eight instances should be tied to the single rotating register input ParallelLoadn. The clock input of all eight instances should be tied to the single rotating register input clock. Create an 8-bit-wide rotating register input DATA IN, whose individual wires DATA IN7 to DATA IN0 are tied to the D input of each instance of the circuit in Figure 5. Likewise, create an 8-bit-wide rotating register

Figure 6: Top-level circuit for Part III.

output Q, whose individual wires Q7 to Q0 are tied to the Q output of each instance of the circuit in Figure 5.

The remaining connections between the eight instances of the circuit in Figure 5 should realize the following behaviour:

1. When ParallelLoadn = 0, the value on DATA IN is stored in the flip-flops on the next positive clock edge (i.e., parallel load behaviour).

2. When ParallelLoadn = 1, RotateRight = 1 and ASRight = 0 the bits of the register rotate to the right on each positive clock edge (notice the bits rotate to the right with wrap around):

Q7Q6Q5Q4Q3Q2Q1Q0

Q0Q7Q6Q5Q4Q3Q2Q1 Q1Q0Q7Q6Q5Q4Q3Q2

…

3. When ParallelLoadn = 1, RotateRight = 1 and ASRight = 1 the bits of the register rotate to the right on each positive clock edge but the most significant bit is replicated. This is called an Arithmetic shift right:

Q7Q6Q5Q4Q3Q2Q1Q0

Q7Q7Q6Q5Q4Q3Q2Q1 Q7Q7Q7Q6Q5Q4Q3Q2

…

4. When ParallelLoadn = 1 and RotateRight = 0, the bits of the register rotate to the left on each positive clock edge. ASRight is ignored:

Q7Q6Q5Q4Q3Q2Q1Q0

Q6Q5Q4Q3Q2Q1Q0Q7 Q5Q4Q3Q2Q1Q0Q7Q6

…

4.1 What to Do

The top-level module of your design should have the following signature declaration:

module part3(clock, reset, ParallelLoadn, RotateRight, ASRight, Data IN, Q);

1. Draw a schematic for the 8-bit rotating register with parallel load. Your schematicshould contain eight instances of the sub-circuit in Figure 5 and all the wiring required to implement the desired behaviour. Label the signals on your schematic with the same names you will use in your Verilog code.

2. Starting with the code in Figure 2 for a flip flop, modify it to have an active-high synchronous reset. Combine this new flip flop with instances of the mux2to1 module from Lab 2 to build the sub-circuit shown in Figure 5. To get you started, Figure 7 is a sample of hierarchical code showing the D flip flop with one of the 2-to-1 multiplexers connected to it.

mux2to1 M1( //instantiates 2nd multiplexer

.y(rotatedata) //output from left most multiplexer

.x(data D) //data D coming in

.s(parallel loadn) //selects input D or rotate

.m(datato dff)

); //outputs to flip flop

flipflop F0( //instantiates flip flop

.d(datato dff)

.q(out Q)

//input to flip flop

//output from flip flop

.clock(clock) //clock signal

.reset(reset)

); //synchronous active high reset

Figure 7: Part of the code for the sub-circuit in Figure 5.

3. Write a Verilog module for the rotating register with parallel load that instantiateseight instances of your Verilog module for Figure 5. This Verilog module should match the schematic in your lab book.

4. Simulate your rotating register with ModelSim to satisfy yourself that your circuit isworking. In your simulation, you should perform the reset operation first. Then, clock the register for several cycles to demonstrate rotation in the left and right directions. (NOTE: If you do not perform a reset first, your simulation will not work! Try simulating without doing reset first and see what happens. Can you explain the results?)

Be prepared to justify that your test cases are enough to give confidence that your circuit is working. When you are satisfied with your simulations, you can submit to the Automarker.

5. Create a new Quartus project for your circuit. You will need a top-level module tomake connections from the instantiation of your part3 module to the switches, keys and LEDs of the DE1-SoC board. Use SW7−0 as the inputs DATA IN7−0 and SW9 as a synchronous active high reset. Use KEY1 as the ParallelLoadn input, KEY2 as the RotateRight input and KEY3 as the ASRight input. Use KEY0 as the clock, but read the important note below about switch bouncing. Be reminded that the KEY s output 0 when pressed and 1, when not pressed. The outputs Q7−0 should be displayed on the LEDs (LEDR7−0).

6. If you have a board, download the compiled circuit into the FPGA chip. Test thefunctionality of the circuit by toggling the various inputs and observing the outputs.

7. If you do not have a board, you can use fake fpga to test that your circuit behaves as expected.

5 Submission

When submitting to the Automarker make sure you have modules declared as shown below as the Automarker will be looking for modules with these exact signatures.

5.1 Part II

For Part II, you need to submit a file named part2.v with the following module in it:

1. module part2(Clock, Reset b, Data, Function, ALUout);

5.2 Part III

For Part III, you need to submit a file named part3.v with the following module in it:

1. module part3(clock, reset, ParallelLoadn, RotateRight, ASRight, Data IN,

Q);
