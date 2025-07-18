These nodes are built to fit on the back of a 2x18650 battery holder, with 2 cells in parallel.

## Common features
  * Solar MPPT charging with CN3791 (buck)
  * USB charging with CN3163 (linear)
  * Vbat -> 3.3 using TLV62568 sync buck for high efficiency
  * Integrated INA3221 for current monitoring of battery, solar, 3v3 voltage and current
  * AHT21 for "is my node currently on fire or underwater" temperature/humidity sensing
## stm32-v1
  * STM32WL with Wio-E5 module
  * Integrated USB serial with CH340N
  * A conveniently shaped header for a [LTE module](https://shop.pimoroni.com/products/clipper-breakout)
