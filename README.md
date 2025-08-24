#  3dsPi

A custom handheld platform powered by Raspberry Pi Zero W, designed to emulate the dual-screen experience of the Nintendo 3DS. Built from scratch with IPS displays, USB-C, and a branded boot flow that feels like a modding monument.


---

## Hardware Overview

| Component        | Description                          |
|------------------|--------------------------------------|
| CPU              | Raspberry Pi Zero W                  |
| Top Screen       | DPI IPS panel (800×480)              |
| Bottom Screen    | SPI TFT (e.g. ST7789)                |
| Power            | USB-C + TP4056 + boost converter     |
| Audio            | PWM → LPF → Amp → Speakers           |
| Inputs           | GPIO buttons + optional joystick     |
| Expansion        | I²C/SPI headers for sensors/modules  |

