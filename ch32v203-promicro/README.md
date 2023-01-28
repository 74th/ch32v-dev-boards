# RISC-V MCU CH32V203 ProMicro サイズ開発ボード (ProMicro sized Dev Board)

## X32Micro v1.1.0

### 部品表 Parts List

| Reference | Parts                                       | Qty |
| --------- | ------------------------------------------- | --- |
| C1-C3, C6 | 0805 Capacitor 100n                         | 4   |
| C4        | 0805 Capacitor 10u                          | 1   |
| C5        | 0805 Capacitor 2.2u                         | 1   |
| C7, C8    | 0805 Capacitor 12p                          | 2   |
| C9, C10   | 0805 Capacitor 22p                          | 2   |
| R1        | 0805 Resister 200                           | 1   |
| R2        | NC or 0805 Resister 10k for BOOT0 Pull Up   | 1   |
| R8        | NC or 0805 Resister 10k for BOOT0 Pull Down | 1   |
| R6-R7     | 0805 Resister 10k                           | 2   |
| R3        | 0805 Resister 0 R                           | 1   |
| R4, R5    | 0805 Resister 5.1k                          | 2   |
| D1        | 0805 LED                                    | 1   |
| J1        | USB2.0 Socket                               | 1   |
| JP1       | Jumper BOOT SW Pull Up / Down               | 1   |
| SW1, SW2  | SW Push                                     | 2   |
| U1        | MCU STM32V103C8T6                           | 1   |
| U2        | SOT-89 Regulator AMS1117-3.3                | 1   |
| Y1        | 3215 Oscillator 32.768k                     | 1   |
| Y2        | 3225 Oscillator 8M                          | 1   |

- CH32V203 など BOOT0 を Pull Up し、BOOT スイッチで GND に繋ぎたい場合
  - R2 を実装してください
  - R8 は未実装 NC にしてください
  - JP1 の中央のランドを △ マークにジャンパしてください
- STM32F103 など BOOT0 を Pull Down し、BOOT スイッチで 3V3 に繋ぎたい場合
  - R2 は未実装 NC にしてください
  - R8 を実装してください
  - JP1 の中央のランドを + マークにジャンパしてください

## CH32V203Micro v1.0.0

![](ch32v203-promicro-v1.0.0-0.jpg)

![](ch32v203-promicro-v1.0.0-1.jpg)

![](ch32v203-promicro-v1.0.0-2.jpg)

![](ch32v203-promicro-v1.0.0-pinout.png)

- BOOTH 販売ページ
- 回路図 Semantics [ch32v203-promicro-v1.0.0-semantics.pdf](ch32v203-promicro-v1.0.0-semantics.pdf)
- PCB [ch32v203-promicro-v1.0.0-pcb.pdf](ch32v203-promicro-v1.0.0-pcb.pdf)

### 部品表 Parts List

| Reference | Parts                             | num |
| --------- | --------------------------------- | --- |
| C1-C3,C6  | 0805 Capacitor 100nF              | 4   |
| C4        | 0805 Capacitor 10uF               | 1   |
| C5        | 0805 Capacitor 2.2uF              | 1   |
| C7,C8     | 0805 Capacitor 12pF               | 2   |
| C9,C10    | 0805 Capacitor 22pF               | 2   |
| D1        | 0805 LED                          | 1   |
| J1        | USB Type-C Socket                 | 1   |
| J2        | PinHeader                         | 1   |
| J3        | PinHeader                         | 1   |
| R1        | 0805 Register 200R                | 1   |
| R2,R6,R7  | 0805 Register 10kR                | 3   |
| R3        | 0805 Register 0R                  | 1   |
| R4,R5     | 0805 Register 5.1k                | 2   |
| SW1       | SW Push                           | 2   |
| U1        | MCU CH32V203CxT6                  | 1   |
| U2        | SOT-89 3.3V Regulator AMS1117-3.3 | 1   |
| Y1        | 3215 Oscillator 32.768kHz         | 1   |
| Y2        | 3225 Oscillator 8MB               | 1   |

![](ch32v203-promicro-v1.0.0-parts.png)
