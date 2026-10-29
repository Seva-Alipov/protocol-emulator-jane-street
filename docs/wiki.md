# Communication Protocol Module for Jane Street Challenge
## Relevant Links
- [Jane Street Blogpost](https://blog.janestreet.com/protocol-emulator-asic-competition/)
## Operation
## Design
- Supports up to 2 devices
- 8-bit per direction link to CPU
- 2 RISC-style cores
- Fixed-length load into memory
### I/O
- Currently discussing whether to use 8 bit bidirectional to the CPU for data or have that includes some muxing
- 2 I/O bits for valid and to select between devices
## Verification
