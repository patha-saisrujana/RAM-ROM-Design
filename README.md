# RAM-ROM-Design
# RAM-ROM-Design

This repository features Verilog designs for three different memory modules: a 64x8 Single Port RAM, a 64x8 Dual Port RAM, and an 8x8 ROM. Each module is designed to serve specific memory-related functionalities and can be used independently in larger digital systems.

## Files:

- **`single_port_ram.v`**: 64x8 Single Port RAM module.
- **`dual_port_ram.v`**: 64x8 Dual Port RAM module.
- **`rom.v`**: 8x8 ROM module.

## 64x8 Single Port RAM:

**Design:**
Implements a single-port RAM with a capacity of 64 words, each consisting of 8 bits.

**Usage:**
Suitable for applications requiring basic memory storage and retrieval with synchronous write and asynchronous read operations.

## 64x8 Dual Port RAM:

**Design:**
Implements a dual-port RAM with separate input and output ports for Port A and Port B, each with a capacity of 64 words of 8 bits.

**Usage:**
Ideal for scenarios requiring simultaneous access from two different sources, enabling parallel read and write operations.

## 8x8 ROM:

**Design:**
Implements a read-only memory (ROM) with 8 words of 4 bits each, initialized with predefined values.

**Usage:**
Useful for applications where fixed data needs to be accessed based on a specified address, such as storing lookup tables or configuration values.
