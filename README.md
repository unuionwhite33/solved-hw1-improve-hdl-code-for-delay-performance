Download Link: https://assignmentchef.com/product/solved-hw1-improve-hdl-code-for-delay-performance
<br>
<strong>Problem 1) </strong>Given the following circuit:

<ul>

 <li>Implement with Verilog a module called JK_FF to realize the function of a JK flip-flop.</li>

 <li>Using the above JK_FF module and some extra loigc, implement with Verilog a module called X torealize the above circuit.</li>

 <li>Write a testbench and run logic simulation. Observe the output waveform. Deduce the functionalityof this circuit.</li>

 <li>Identify the critical path in the above logic diagram and use color to mark this path. How manycritical paths are there? Assuming the wire delay is negligiable.</li>

</ul>

<strong>Problem 2)</strong>  Given the following FIR circuit in Verilog code,




<ul>

 <li>Write a test bench for this code and perform logic simulation, and print out the waveform.</li>

 <li>Let the Vivado generate the logic diagram of your synthesized circuit. Print it out.</li>

 <li>Compare your Vivado output with the following diagram, are these two diagrams the same instructure?</li>

</ul>

3) For both Vivado output and the above diagram, find their throughput (bits/clock cycle), Latency (clock cycles), and Timing (Critical path delay). OF course, if these two diagrams are the same, you only need to do once.

<strong>Problem 3)  </strong>

Use Page 7-10 of Lecture  3: Architecting for Speed in Digital Design as example.

1) Translate the following C code into a Verilog code without pipelining. List your circuit implementation and its testbench. Also print out the waveform for simulation.

x = 0; y = 0;

for (i=0; i &lt; 3; i++ ){ x = x + y;

}

<ul>

 <li>For your code in 1), find its throughput (bits/clock cycle), Latency (clock cycles), andTiming (Critical path delay).</li>

 <li>Now, pipeline your design in 1). Use 3 stages. List your circuit implementation and its testbench. Also print out the waveform for simulation.</li>

 <li>For your code in 3), find its throughput (bits/clock cycle), Latency (clock cycles), andTiming (Critical path delay).</li>

</ul>