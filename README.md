# STM32 LED Switcher

A multi-mode LED controller developed in C for the STM32 Nucleo-F401RE microcontroller using the STM32 HAL library.

## Features

- Multiple LED operating modes controlled through a button
- PWM-based LED brightness control
- GPIO external interrupts (EXTI) and timer callbacks
- Button debouncing and long-press detection
- Finite-state machine for managing LED modes
- Direct timer register access
- Low-power CPU waiting using the `WFI` instruction

## Technologies

- C
- STM32 Nucleo-F401RE (STM32F401RE)
- STM32 HAL
- GPIO, EXTI, Timers, PWM
- STM32CubeIDE

## Overview

The project demonstrates interrupt-driven embedded programming, microcontroller peripheral configuration, and hardware-level interaction using both the HAL library and direct register access.

## Hardware

- STM32 Nucleo-F401RE
- LEDs and a push button
- Basic electronic components
