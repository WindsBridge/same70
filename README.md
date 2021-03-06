# SAME70

This project aims for in-depth exploration of ARM Cortex-M microcontrollers.

We will use an Atmel SAME70 (Cortex-M7) microcontroller development board for this:
the SAME70 XPlained board as manufactured by Atmel. It is pretty cheap (30 to 40 US dollars), and quite powerful, as Cortex-M microcontrollers go.

Important web pages
-------------------

Atmel was acquired by MicroChip in 2017. The old Atmel website is slowly but surely being
transferred to the Microchip website.

Atmels [SAM E70 XPlained Evaluation Kit information](http://www.microchip.com/DevelopmentTools/ProductDetails.aspx?PartNO=ATSAME70-XPLD) provides information about the evaluation kit.

The [SAME70-XPLD Xplained User Guide](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-44050-Cortex-M7-Microcontroller-SAM-E70-XPLD-Xplained_User-guide.pdf) contains header pinouts and schematics of the SAME70 PCB.

Table of Contents
-----------------

1. [OpenOCD](markdown/01_OpenOCD.md)
2. Building a GCC toolchain with Newlib support
3. Newlib in-depth
4. C and C++ support
5. [Startup sequence of the SAME70 microcontroller](markdown/05_StartupSequence.md)
6. Low-power software design
7. Using an RTOS
8. [The CMSIS standards](markdown/08_CMSIS.md)
9. [The Atmel Software Framework (ASF)](markdown/09_ASF.md)
10. Linker script
11. The SAM-BA protocol
12. Programming in Rust
