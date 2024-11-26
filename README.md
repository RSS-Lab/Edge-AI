# SPIKE
The Spike simulator is a command-line application for RISC-V development. It allows for both 32-bit and 64-bit simulations and supports multiple variants of RISC-V types. It’s an alternative to using the Segger emSim simulator, which has both a graphical mode and a command line mode and. It’s also more up-to-date and widely-used than the RVS simulator that we have been using at York University for a few years.
# Prerequisites
For the installation process, you'll need a Linux-based system. If you're on Windows, you can use WSL (Windows Subsystem for Linux) or VirtualBox to create a virtual machine with the necessary Linux environment. VirtualBox recommanded.

Virtual Machine Specifications:
To set up your virtual machine, you can create a VM with the following specifications:

CPU: 2+ cores (depending on your system resources)

RAM: 4GB (minimum) or more

Storage: 60GB+ of disk space (to accommodate the Linux system and  riscv toolchains)

Operating System: A Linux distribution like Ubuntu 22.04 LTS

Once the VM is created, you'll be able to install Spike and the required development tools on it. This setup will allow you to run simple C and assembly programs using the RISC-V simulator and use GDB to inspect and debug the contents of registers.

- To install **WSL** on Windows, you can follow the guide [here](https://docs.microsoft.com/en-us/windows/wsl/install).
- To install **Ubuntu** on VirtualBox, use this [guide](https://www.youtube.com/watch?v=p4P0s9GtDDM).



