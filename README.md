# wozmon.z80
Wozmon for the gameboy (sm83 processor) in gbz80 assembly.

Based on: https://github.com/jefftranter/6502/blob/master/asm/wozmon/wozmon.s

Original wozmon.z80 is almost a 1 to 1 translation of the 6502 assembly into gbz80. This makes heavy use of the hl registers and HRAM variables.

Optimized wozmon.z80 makes use of code better optimized for the sm83 processor.

Both are tested and working on my gameboy virtual terminal: https://github.com/RubenZwietering/gameboy-virtual-terminal