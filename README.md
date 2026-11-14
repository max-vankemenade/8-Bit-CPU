# 8-Bit-CPU
Programmable 8-Bit CPU in Emulator

I designed and wired a working 8-bit CPU in the “Digital Logic Sim” emulator created by YouTuber Sebastian Lague. It features an accumulator, a status register, a program counter, 256 bytes of RAM, a stack pointer, and a block where you can write code with its own instruction set, which is interpreted in the control register. When designing the CPU, I had never before seen the architecture or conventions of a real CPU, so it is neither efficient nor realistic (for example, it does not operate according to the von Neumann principle). The CPU was created purely based on my ideas of how I would design a programmable CPU.

<img width="1272" height="676" alt="image" src="https://github.com/user-attachments/assets/2bfa992c-0d98-44ef-a41e-161f2a3f48e8" />

The lines at the top and bottom represent buses for inputs and outputs between the components. On the left, you can load a variable x into the program, which you can then use directly in the SRC block (the code). On the right, you can see the output of the accumulator. Blocks marked with a “-” are gates that are opened only by certain commands via the control register in which the translator is located.
