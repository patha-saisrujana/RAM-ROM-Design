# RAM-ROM-Design
This repository features Verilog designs for three different memory modules: <br>a 64x8 Single Port RAM, a 64x8 Dual Port RAM, and an 8x8 ROM. Each module is designed to serve specific memory-related functionalities and can be used independently in larger digital systems.<br>
Files:
single_port_ram.v: 64x8 Single Port RAM module.<br>
dual_port_ram.v: 64x8 Dual Port RAM module.<br>
rom.v: 8x8 ROM module.<br>
64x8 Single Port RAM:<br>
Design: Implements a single-port RAM with a capacity of 64 words, each consisting of 8 bits.<br>
Usage: Suitable for applications requiring basic memory storage and retrieval with synchronous write and asynchronous read operations.<br>
64x8 Dual Port RAM:<br>
Design: Implements a dual-port RAM with separate input and output ports for Port A and Port B, each with a capacity of 64 words of 8 bits.<br>
Usage: Ideal for scenarios requiring simultaneous access from two different sources, enabling parallel read and write operations.<br>
8x8 ROM:<br>
Design: Implements a read-only memory (ROM) with 8 words of 4 bits each, initialized with predefined values.<br>
Usage: Useful for applications where fixed data needs to be accessed based on a specified address, such as storing lookup tables or configuration values.
