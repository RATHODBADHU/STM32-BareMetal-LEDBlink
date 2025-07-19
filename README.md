# STM32-BareMetal-LEDBlink
LED Blink

# STM32 Bare-Metal LED Blink (PA5)

This project demonstrates how to blink an LED connected to pin PA5 on an STM32L476RG microcontroller using register-level programming (no HAL or CMSIS).

## Features
- Enables GPIOA using RCC AHB2ENR
- Configures PA5 as a general-purpose output
- Toggles PA5 to blink LED using software delay

## Target
- MCU: STM32L476RG (e.g., Nucleo-L476RG board)
- Language: C (bare-metal)
- Toolchain: Any ARM-GCC based compiler (STM32CubeIDE, Keil, etc.)

## Getting Started
Just compile and flash `main.c` to your STM32 board. PA5 (usually onboard LED on Nucleo) will blink.
