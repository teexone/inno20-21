# Introduction to Computer Architecture

## Classes of Computers
- Personal Mobile Device (PMD - smartphones, tablet)
  - Emphasis on energy efficiency and real time.
- Desktop Computing
  - Emphasis on price-performance
- Servers
  - Emphasis on availability, scalability, throughput
- Cluster / Warehouse Scale Computers
  - User for _SaaS_, cloud
  - Emphasis on availability and price-performance
  - Sub-class: Supercomputers, emphasis: floating-point performance and fact internal networks
- Embedded Computers
  - Emphasis: price, robustness

  ISA: Industry Standard Architecture

  | Problem Solution Stack |
  | - |
  | Problem |
  | Algorithm |
  | Data structure user programs
  | System programs
  | Architecture
  | Microarchitecture
  | Circuits
  | Electrons

## Von-Neiman Architecture

  - Stored program
    - Instructions stored in a linear memory array
    - Memory is unified between instructions and data
      - The interpretation of a stored value depends on the control signal
  - Sequential instruction processing
    - One instruction processed
    - Program counter identifies the current instruction
    - Program counter is advanced sequentially except for control transfer
    instructions

## Parts of computer

### CPU

Parts of CPU:
- Control Unit (CU)
- Arithmetic-Logic Unit (ALU)
- Registers (32/64 or custom for embedded)    

### Memory
- System Main Memory (stores a program). Divided into cells, each cell
has address.
