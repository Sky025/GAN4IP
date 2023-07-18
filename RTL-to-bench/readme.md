The conversion from RTL to .bench netlist is crucial in hardware design and verification workflows. This repository aims to simplify this process by offering a collection of scripts and utilities that automate the conversion using ABC and Yosys, two widely used synthesis open-source tools in the hardware design community.

To convert a Register Transfer Level (RTL) description to a .bench file format using the Yosys synthesis tool and the ABC logic synthesis and optimization tool, you can follow these steps:

Install Yosys and ABC:

Yosys: Yosys is an open-source synthesis tool. You can find installation instructions for Yosys on the official GitHub repository: 
https://github.com/YosysHQ/yosys
ABC: ABC is a logic synthesis and optimization tool. You can find installation instructions for ABC on the ABC GitHub repository: 
https://github.com/berkeley-abc/abc
Prepare your RTL description:

1. Write or obtain the RTL description of your circuit in a supported format, such as Verilog (.v) or VHDL (.vhdl).

2. Invoke Yosys/Synopsys Design Compiler to perform synthesis

3. Replace your_rtl_file.v with the path to your RTL file in the ABC compiler, and your_bench_file.bench with the desired output filename for the .bench file.

4. Verify the generated .bench file:

Once the command completes, you should have a .bench file generated in the current directory.

Open the .bench file with a text editor to verify that it contains the desired Boolean logic representation of your circuit.
That's it! You have successfully converted your RTL description to a .bench file format using Yosys and the ABC compiler. The .bench file represents the circuit in terms of Boolean equations and is commonly used for logic simulation and further optimizations.
