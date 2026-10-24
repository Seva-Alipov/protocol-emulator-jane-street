# Project Planning
## Architecture Discussion
[diagram](https://lucid.app/lucidchart/af35344a-bb3d-4a40-b129-fcdfabd9807e/edit?viewport_loc=-1281%2C-12%2C3594%2C2659%2C0_0&invitationId=inv_cbc1036d-c56c-4b2a-b7f8-2eb852099db9)
- 2 or 4 devices, with single 8-bit link to CPU
- 1 RISC-style core/pin
- Fixed-length load into memory

### I/O
- Currently discussing whether to use 8 bit bidirectional to the CPU for data or have that includes some muxing
- 2 I/O bits for valid and to select between devices

### Instruction Set
TBD Next meeting?
