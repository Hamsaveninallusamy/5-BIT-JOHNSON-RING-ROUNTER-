# 5-BIT-JOHNSON-RING-ROUNTER
The 5-Bit Johnson and Ring Counters project implements two types of sequential counters using Verilog HDL: a Johnson Counter and a Ring Counter. The module takes an input clock signal and a reset signal to control the counters' operations. The Johnson Counter generates a 5-bit sequence by shifting the bits cyclically while inverting the MSB and appending it to the LSB. The Ring Counter creates a sequence by shifting the bits in a loop with the MSB being fed back to the LSB. Both counters are resettable, ensuring predictable initialization. The design is compact and efficient, making it suitable for digital systems requiring cyclic sequence generation or state machines.
