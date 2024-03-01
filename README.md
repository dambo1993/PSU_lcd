# PSU_lcd

Projekt GUI na kolorowym wyświetlaczu sterującego zasilaczem laboratoryjnym, który ma możliwość komunikacji przez RS232.

## Hardware

Wykorzystane moduły sprzętowe:
- evalboard STM32F746G-DISCO
  - mikrokontroler STM32F746NGH6, Cortex-M7 @216MHz
  - Wyświetlacz 4,3 cala LCD-TFT WQVGA 480x272 pikseli z pojemnościowym touch-panelem
- zasilacz KORAD KD3005P

## Firmware

Projekt oparty o bibliotekę TouchGFX w wersji 4.23.
Używane IDE to STM32CubeIDE.
