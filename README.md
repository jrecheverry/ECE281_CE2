ECE281_CE2
==========

This computer exercise explored the two ways to code using VDHL: behavioral and structural. We created a 2-4 bit decoder using behavioral and structural programming to show the differences in each.

#Decoder_Structural Simulation Results and Analysis


![Structural](https://raw2.github.com/jrecheverry/ECE281_CE2/master/structural_testbench.png)


#Decoder_Behavioral Simulation Results and Analysis

![Behavioral](https://raw2.github.com/jrecheverry/ECE281_CE2/master/behavioral_testbench_pic.PNG)

show that both of these screen shots show the same functionality, however, the structural testbench was eaiser to write because it incorporated all of the functions of the circuit into a few lines of code instead of writing out a truth table for the entire testbench.

#How does a decoder work

How does a decoder work and how can that funcitonality be useful in the context of computer memory?
A decoder is the exact opposite of an encoder. It converts the coded inputs into coded outputs. It is a collection of logic gates that are arranged in a specific way so that they can breakdown any combination of inputs to a set of terms that are all set to 0 apart from one term. Thus when one input changes, two output terms will change.  Decoders are used in computers to decode the addresses for memory. A read-only memory can be made from a decoder and multiple input OR gates.(explanation taken from CAL - Digital Logic).
