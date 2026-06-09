NASSCOM RISC-V based MYTH Program Notes
This repository contains day-wise notes, lab writeups, and lecture documentation for the NASSCOM RISC-V based MYTH program.

The workshop covered:

RISC-V ISA fundamentals
CPU microarchitecture
pipelining
hazard handling
register files
ALU operations
branch/jump control
load/store memory operations
timing-abstract hardware design
(MakerChip link, file and screenshots at EOF)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
RV Day 1 - Introduction to RISC-V ISA and GNU compiler toolchain

D1SK1 - Introduction to RISC-V basic keywords
D1SK2 - Labwork for RISC-V software toolchain
D1SK3 - Integer number representation

This lecture introduces the NASSCOM RISC-V based MYTH (Microprocessor for You in Thirty Hours) program conducted by VSD (VLSI System Design).

The session gives a high-level overview of:

the course structure
RISC-V fundamentals
the hardware-software relationship
the learning roadmap for the workshop


RV Day 2 - Introduction to ABI and basic verification flow
D2SK1 - Application Binary Interface (ABI)
D2SK2 - Lab work using ABI function calls
D2SK3 - Basic verification flow using iverilog

This lecture introduces the concept of the Application Binary Interface (ABI).

The ABI acts as the interface between:

application programs
operating systems
compilers
processor architecture
The lecture explains:

why ABI is required
software-hardware interaction
binary compatibility

[DAY 1-2](https://github.com/angelinemalarvizhi/vsd-riscv/tree/fba01d20a6d4f6e3aca29c30376c15610c8edcf8/DAY%201-2/IMAGE)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------

RV Day 3 - Digital Logic with TL-Verilog and Makerchip

This lecture marks the beginning of:

Digital Logic Design
TL-Verilog
Makerchip platform
RISC-V CPU implementation
The lecture introduces:

modern silicon design methodology TL-Verilog Makerchip IDE digital logic concepts pipelining concepts future workshop roadmap

The instructor repeatedly emphasizes:

accessibility of silicon design productivity improvements practical hands-on learning building a RISC-V CPU from scratch

D3SK1 - Combinational logic in TL-Verilog using Makerchip -- https://www.makerchip.com/v140/ide/~0n5fGh3q/p-066hGD

D3SK2 - Sequential logic -- https://www.makerchip.com/v140/ide/~0n5fGh3q/p-048h73

D3SK3 - Pipelined logic -- https://www.makerchip.com/v140/ide/~0n5fGh3q/p-098hYD

D3SK4 - Validity -- https://www.makerchip.com/v140/ide/~0n5fGh3q/p-08qhw7

D3SK5 - Hierarchy concept -- https://www.makerchip.com/v140/ide/~0n5fGh3q/p-058hWj

MAKERCHIP LAB URL -- https://github.com/angelinemalarvizhi/vsd-riscv/blob/fba01d20a6d4f6e3aca29c30376c15610c8edcf8/DAY%203/URL/MAKERCHIP%20LABS

MAKERCHIP LAB IMAGES -- https://github.com/angelinemalarvizhi/vsd-riscv/tree/fba01d20a6d4f6e3aca29c30376c15610c8edcf8/DAY%203/IMAGES
-------------------------------------------------------------------------------------------------------------------------------------------------------------------

RV Day 4 - Basic RISC-V CPU micro-architecture

Overview
The lecture introduces:

D4SK1 - Introduction to Simple RISC-V Micro-architecture

CPU microarchitecture
program counter
instruction memory
decode logic
register file
ALU
branch computation
load/store datapaths
memory addressing
writeback
instruction flow

D4SK2 - Fetch and decode -- https://www.makerchip.com/v140/ide/~0n5fGh3q/p-0Y6h65 AND https://www.makerchip.com/v140/ide/~0n5fGh3q/p-0Z4hoy

D4SK3 - RISC-V control logic -- https://www.makerchip.com/v140/ide/~0n5fGh3q/p-02RhEx

MAKERCHIP LAB URL -- https://github.com/angelinemalarvizhi/vsd-riscv/blob/fba01d20a6d4f6e3aca29c30376c15610c8edcf8/DAY%204/URL/MAKERCHIP%20LABS

MAKERCHIP LAB IMAGES -- https://github.com/angelinemalarvizhi/vsd-riscv/tree/fba01d20a6d4f6e3aca29c30376c15610c8edcf8/DAY%204/IMAGES
-------------------------------------------------------------------------------------------------------------------------------------------------------------------

RV Day 5 - Complete Pipelined RISC-V CPU micro-architecture

D5SK1 - Pipelining the CPU

Overview
This lecture introduces CPU pipelining concepts using the previously built RISC-V core. The lecture focuses on:

CPU pipelining
waterfall pipeline representation
instruction overlap
pipeline stage partitioning
performance improvement through pipelining
inter-instruction dependencies
control hazards
read-after-write hazards
The lecture explains:

why pipelining improves performance
how instructions overlap in execution
how timing dependencies create hazards
why some datapath dependencies become problematic after pipelining
This lecture establishes the conceptual foundation for:

pipelined CPU design
hazard analysis
pipeline timing reasoning
inside the RISC-V processor.

D5SK2 - Solutions to Pipeline Hazards -- https://www.makerchip.com/v140/ide/~0n5fGh3q/p-0NxhMV AND https://www.makerchip.com/v140/ide/~0n5fGh3q/p-0Mjh62

D5SK3 - Load/Store Instructions and Completing RISC-V CPU -- https://www.makerchip.com/v140/ide/~0n5fGh3q/p-0O7h22

MAKERCHIP LAB URL -- https://github.com/angelinemalarvizhi/vsd-riscv/blob/fba01d20a6d4f6e3aca29c30376c15610c8edcf8/DAY%205/URL/Makerchip%20labs

MAKERCHIP LAB IMAGES -- https://github.com/angelinemalarvizhi/vsd-riscv/tree/fba01d20a6d4f6e3aca29c30376c15610c8edcf8/DAY%205/images
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
