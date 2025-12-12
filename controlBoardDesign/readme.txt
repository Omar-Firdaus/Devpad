Project Name: Macropad
Project Version: #135a8c46
Project Url: https://www.flux.ai/omarfirdaus1/macropad

Project Description:
Compact Seeed XIAO RP2040 Macropad with 3×4 MX Matrix, Dual Encoders, OLED, and SK6812 MINI-E Chain (Rows: GPIO0–2, Cols: GPIO3–6, OLED: GPIO8/9, Encoders: GPIO7/10–14, Button: GPIO15, LED_DATA Conflict on GPIO6) #XIAORP2040 #macropad #I2C #MXMatrix #sk6812

Project Properties:

Power Requirements:
USB

Software:
Arduino

Domain:
Consumer Electronics

Human Interface:
Buttons,Rotary encoder,Display

System Architecture:
```mermaid
flowchart TD
    Power["Power Supply"]
    MCU["MCU: Seeed XIAO RP2040"]
    Top["OLED 0.91" I2C, Encoders & Pushbutton"]
    Bottom["3×4 MX Key Matrix & SK6812 LED Chain"]
    Power --> MCU
    Power --> Top
    Power --> Bottom
    MCU --> Top
    MCU --> Bottom
```

Operating Voltage:
5


