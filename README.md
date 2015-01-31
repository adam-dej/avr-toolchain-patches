# AVR Toolchain patches

Patches adding support for ATTiny441 and ATTiny841 to the opensource AVR toolchain.

## avr-gcc patch

This patch modifies configuration of the avr-gcc and defines the MCU name for the compiler.

This patch is intended for avr-gcc version 4.9.2

## avr-libc patch

This patch modifies configuration of the avr-libc, adds startup code and a header file defining addresses of peripheral registers.

This patch is intended for avr-libc version 1.8.1

## Building

Download appropriate versions of avr-gcc (4.9.2) and avr-libc (1.8.1), patch them and then just follow instructions in the packages.

Build avr-gcc first, avr-libc second. Also make sure that you have avr-binutils installed before building avr-gcc.

### Building in Arch Linux

Arch Linux PKGBUILDs are included for convenience.