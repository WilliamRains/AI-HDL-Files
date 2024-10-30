<h1>Welcome to AI-HDL!</h1> 

In this folder you will find the following source files required to build the first iteration of your digital watch. However,
these files will only contain the required inputs and outputs of the modules. It is up to you to create them by prompting
your language model of choice. Below are explanations of each module to help you better understand the baseline project:

<ul>
<li>seven_segment_display.v: Manages the display of the stopwatch time on the Basys 3's four-digit seven-segment display.</li>
<li>clock_divider.v: Divides the 100 MHz Basys 3 clock down to a slower frequency suitable for timing and display purposes.</li>
<li>buttonDebouncer.v: Provides stable, debounced input signals for the start/stop and reset buttons.</li>
<li>top_level.v: The main module that integrates all components.</li>
<li>stopwatch.v: Implements the stopwatch logic, handling start/stop and reset functionality.</li>
</ul>
It will also include 1 simulation source that can be used to test the output of your code:
<ul>
<li>top_level_tb.v: A testbench that simulates the top_level module, allowing you to test the full stopwatch functionality in Vivado.</li>
</ul>
Once all files have been generated and debugged, press the "Run Simulation" button on Vivado to generate the waveform for the 
behavioral simulation. This will tell you whether or not the modules are functioning properly.