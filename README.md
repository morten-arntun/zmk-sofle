# Sofle

- [Chinese](README_Chinese.md)
- [English](README.md)

## Update List

- 2024/12/21
  1. Added support for zmk-studio (just refresh the left hand to use).
- 2024/10/24
  1. Modified power supply mode to reduce power consumption.
  2. Fixed the automatic shut-off feature for RGB power supply.
- 2025/8/22
  1. update the soft off.When you press the keys Q, S and Z simultaneously and hold them for 2 seconds, the keyboard will enter a deep sleep state and cannot be awakened by pressing the keys. This function can be used when carrying it outside. The activation method is to press the reset switch once.
  2. This month, I also updated the ultra-thin versions of the corne and sofle cases. The frame and base plate have been thickened, and the opening of the reset switch has been adjusted, so that the reset switch can be easily pressed. At present, we are still conceptualizing how to design the shell with an inclined bracket.If you have carefully examined a PCB, you will notice that there are reserved interfaces for expansion IO. I wonder if anyone has been able to utilize them,I will try it！
  3. The GIF animations on the right-hand keyboard screen have been removed, which will significantly reduce the power consumption of the right-hand keyboard.
 
-2026/6/22
The keyboard now supports key remapping via DYA STUDIO. This PC software offers better key remapping functionality than ZMK Studio. Website: https://studio.dya.cormoran.works/ https://studio.dya.cormoran.works/

-2026/09/05
Added support for configuring combos and macros via DYA studio. Also added Norwegian locale syntax to the keymap, for better compatability with Norwegian input modes.

## Sofle Keymap

![Sofle键位图](keymap-drawer/eyelash_sofle.svg)
