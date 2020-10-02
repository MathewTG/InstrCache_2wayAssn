# InstrCache_2wayAssn
A simple example of a 2-way associative Instruction Cache 

Part of Advanced VLSI Design Coursework
Verilog code for a Memory subsystem with Instruction cache, Cache controller and Main memory for a processor implementation.

Some Implementation Details
1. The word size of the processor is 32-bits. The processor requests for memory access by
sending 32-bit address.
2. Instruction Cache specifications:
  - Hit Time for Cache is one clock cycle
  - Cache is 2-way set associative with 4 sets
  - Block size is 2 words
  - LRU replacement policy is used
3. Cache controller should control the processor, cache and main memory interaction.
4. For simplicity assume that the main memory is byte addressable and has a capacity of
32 words (128 bytes). Also the main memory access requires 10 clock cycles. 
