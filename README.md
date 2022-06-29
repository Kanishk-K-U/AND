# Design and synthesis of AND Gate using _verilog_ and _YOSYS_
<p>
The output of the AND gate, a main logic gate, is equal to the product of its inputs. Only when both inputs are high does this gate's output become high; otherwise, it becomes low. 
</p>
<p >
  <div align="center" >
 <img src="https://i0.wp.com/technobyte.org/wp-content/uploads/2020/01/AND-gate.png?ssl=1">
  </div>
</p>
<p >
  <div align="center" >
 <img src="https://github.com/Kanishk-K-U/AND/blob/main/AND.png" align="centre" height="540" width="960">
  </div>
</p>
# Design and Implementation

<p>
I used Verilog's behavioural modelling approach to create the AND logic gate. In the Verilog HDL, behavioural modelling represents the highest level of abstraction. The algorithm of the design, which is the fundamental knowledge for any design, is all that is required of the designer. The specifics are not stated; this level models the behaviour of the circuits. This is advantageous since it frees the designer from having to deal with challenging calculations or circuits. A straightforward truth table would be adequate.
</p>

## Truth Table

<p >
  <div align="center" >
 <img src="https://www.allaboutcircuits.com/uploads/articles/two-input-and-gate-truth-table.jpg">
  </div>
</p>

_From the truth table equation using k-maps minimizing:_ Y = A.B or Y = A & B

# Synthesis of AND Gate
<p >
  <div align="center" >
 <img src="https://github.com/Kanishk-K-U/AND/blob/main/AND%20sy.png">
  </div>
</p>
