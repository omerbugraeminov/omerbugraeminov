# Hi, I'm Ömer Buğra 👋
 
I like figuring out how computers work from the bottom up, so I'm building my own CPU in Verilog.
 
## 🐍 Venom CPU
 
[**Venom**](https://github.com/omerbugraeminov/venomcpu) is an 8-bit processor I'm designing from scratch and running on a Sipeed Tang Nano 20K FPGA.
 
<a href="https://github.com/omerbugraeminov/venomcpu/tree/extended">
  <img src="https://raw.githubusercontent.com/omerbugraeminov/venomcpu/extended/docs/core.svg" alt="Venom Extended core" width="600">
</a>
- **Venom** (`main`): single-cycle CPU with 16 instructions, 8 registers, multi-cycle MUL/DIV
- **Venom Extended** (`extended`): 5-stage pipeline with forwarding, load-use stall and branch flush, ~95 MHz Fmax
- **Next:** cache and a general memory interface so anyone can attach external RAM, then **Venom Dual** (dual core)
## 🛠️ Tools
 
![Verilog](https://img.shields.io/badge/Verilog-1f425f?style=for-the-badge)
![FPGA](https://img.shields.io/badge/FPGA-Tang%20Nano%2020K-red?style=for-the-badge)
![Gowin](https://img.shields.io/badge/Gowin%20EDA-0A66C2?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
