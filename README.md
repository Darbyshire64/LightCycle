# LightCycle
A Custom Set of Bike Lights with indicators made for my Bike Using NeoPixels. Made for @hackclub [REDACTED] YSWS


### Control Board
 - ESP32-S3
 - Status Neopixel
 - Acceleromiter - Intelligent Lighting Control
 - 3 Position Switch For Indicators - Left, Off, Right
 - 0.96inch OLED - Show Light Status of indicator's
 - 2 Postion Switch for On Off

 ### Lighting Pannel

  - A Grid of 2x8 Neopixel LED's
  - 4 Pin JST Connector's Links to main board

### Inteligent Lighting 

| Bike State | Lighting State |
|------------|----------------|
| Stopped    | HL, BL, TL = 10%  |
| Bike Accelerating | HL + TL = 50%  |
| Rapid Deceleration | BL = 100% |


