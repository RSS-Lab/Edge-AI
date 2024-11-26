# SPIKE
The Spike simulator is a command-line application for RISC-V development. It allows for both 32-bit and 64-bit simulations and supports multiple variants of RISC-V types. It’s an alternative to using the Segger emSim simulator, which has both a graphical mode and a command line mode and. It’s also more up-to-date and widely-used than the RVS simulator that we have been using at York University for a few years.
# Prerequisites
For the installation process, you'll need a Linux-based system. If you're on Windows, you can use WSL (Windows Subsystem for Linux) or VirtualBox to create a virtual machine with the necessary Linux environment. VirtualBox highly recommanded.

Virtual Machine Specifications:
To set up your virtual machine, you can create a VM with the following specifications:

CPU: 2+ cores (depending on your system resources)

RAM: 4GB (minimum) or more

Storage: 60GB+ of disk space (to accommodate the Linux system and  riscv toolchains)

Operating System: A Linux distribution like Ubuntu 22.04 LTS

Once the VM is created, you'll be able to install Spike and the required development tools on it. This setup will allow you to run simple C and assembly programs using the RISC-V simulator and use GDB to inspect and debug the contents of registers.

- To install **WSL** on Windows, you can follow the guide [here](https://docs.microsoft.com/en-us/windows/wsl/install).
- To install **Ubuntu** on VirtualBox, windows 11 use this [guide](https://www.youtube.com/watch?v=L9ya49O5CIY).
- To install **Ubuntu** on VirtualBox, windows 10 use this [guide](https://www.youtube.com/watch?v=f3QdUOD2vOs).


# Installation Guide for Spike RISC-V ISA Simulator

For detailed information about the Spike simulator, visit the official documentation [here](https://www.yorku.ca/professor/drsmith/2024/07/28/getting-started-with-risc-v-spike-simulator/)

To install the Spike RISC-V ISA Simulator, follow the step-by-step instructions provided on this [page](https://github.com/riscv-software-src/riscv-isa-sim).

To set up the RISC-V GNU Compiler Toolchain, refer to the installation steps available on this [page](https://github.com/riscv-collab/riscv-gnu-toolchain/blob/master/README.md).

To install the Proxy Kernel, follow the instructions provided on this [page](https://github.com/riscv-software-src/riscv-pk).

