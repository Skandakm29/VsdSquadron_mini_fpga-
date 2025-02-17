
# VSD Squadron Mini FPGA Project

## Overview
This project demonstrates FPGA implementation on the VSDSquadron Mini FPGA board using Verilog and open-source tools (Yosys, NextPNR, and IceStorm). It includes an internal oscillator, a frequency counter, and RGB LED control.

## Tools Required
- **Yosys** - Logic synthesis
- **NextPNR** - Placement & routing
- **IceStorm** - Bitstream generation
- **Git** - Version control

## Pin Mappings
| Signal    | FPGA Pin | Description          |
|-----------|---------|----------------------|
| led_red   | 39      | Red LED Output       |
| led_blue  | 40      | Blue LED Output      |
| led_green | 41      | Green LED Output     |
| hw_clk    | 20      | External Clock Input |
| testwire  | 17      | Debugging Signal     |

## Build & Flash Instructions
### Clone the Repository
```sh
git clone https://github.com/Skandakm29/VsdSquadron_mini_fpga-.git
cd VsdSquadron_mini_fpga-
```
## Compile and Flash the FPGA
```sh
make build
make flash
```
## Expected Behavior
Blue LED remains ON (controlled by SB_RGBA_DRV).
## License
This project is open-source under the MIT License.

## Contact
Email: kmskanda29@gmail.com

