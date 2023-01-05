PMOD Composite Output Board
===========================

Designed for use with FPGA boards used as DIY MEGA65 machines.

The DAC uses 4 FPGA pins per channel. It is designed for the
FPGA to massively over-sample the outputs to obtain 4 bits of
precision per FPGA line. Thus 16 bit precision per line should
be possible.  Most of the components on the board are the filter
to smooth out the switching noise from driving the pins at 540MHz
(270MHz DDR) to produce a nice clean 13.5MHz clocked composite
signal.  Should work fine as an audio DAC, too.

Design is all hole-through for easy assembly at home.
