<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project uses two 4-bit inputs, A and B, and puts them on the 8-bit ui_in signal to produce an 8-bit product S on uo_out. This is the implementation of a 4-bit unsigned multiplier that performs multiplication combinationally use array multiplier.

## How to test

To test the project, it needs two 4-bit values to be applied to ui_in by making A the top four bits and B the bottom four. Start the process by asserting the enable and disabling the reset to receive the resulting product after a few clock cycles.

## External hardware

No external hardware is used as this is all done digitally.
