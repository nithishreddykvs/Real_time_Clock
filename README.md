# Digital Clock with Seven-Segment Display

## Description

This project is a digital clock implemented using Verilog. The design accurately tracks hours, minutes, and seconds and can be deployed on FPGA boards or simulated using software like Xilinx Vivado or ModelSim.

## Features

- Displays time using a seven-segment display

- Converts binary-coded decimal (BCD) for proper numerical representation

- Implements a debounce circuit to filter noisy button presses

- Modular design with separate components for different functionalities

- Simulates real-time clock behavior

## Installation & Usage

1. Clone the repository:
   ```sh
   git clone <repository-link>
   ```
2. Open the project in your preferred Verilog simulation tool (Vivado, ModelSim, etc.).
3. Run the testbench to simulate the functionality.
4. Synthesize and implement it on an FPGA if required.
5. Use the button inputs to adjust time settings as needed.

## Hardware Requirements 

- FPGA development board (Basys 3)
- Compatible simulation software (Vivado, ModelSim, etc.)
- Power supply (if using FPGA)

## Technologies Used

- Verilog HDL
- FPGA implementation (Basys 3)
- Xilinx Vivado/ModelSim for simulation

## Code Explanation

The digital clock consists of:

1. **Clock Divider**: Generates a slower clock signal from the FPGA’s main clock to drive the clock updates.

2. **Binary-to-BCD Converter**: Converts the binary time format into BCD for display on the seven-segment module.

3. **Seven-Segment Display Driver**: Controls the display segments based on the BCD values.

4. **Debounce Logic**: Filters out unintended multiple presses from mechanical buttons.

5. **Top Module**: Integrates all submodules to function as a complete digital clock system.

## License

This project is open-source under the MIT License.

## Contributors

- **Nithish Reddy KVS**
- **Veddesh RGM**
- **Niranjan P**

For any queries contact - nithishreddy.k.v.s\@gmail.com
