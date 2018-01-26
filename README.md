# This Project for trainee and developer.
[How to](#how-to)
  * [Lesser than 5V, with voltage booster](#lesser-than-5v-with-voltage-booster)
  * [Higher than 5V, with internal voltage regulator](#higher-than-5v-with-internal-voltage-regulator)
  * [Higher than 5V, with external voltage regulator](#higher-than-5v-with-external-voltage-regulator)
  * [Higher than 5V, activated on demand](#higher-than-5v-activated-on-demand)
- [Voltage divider ratio](#voltage-divider-ratio)
- [Examples](#examples)
  * [Single cell Li-Ion on 3.3V MCU](#single-cell-li-ion-on-33v-mcu)
  * [Double cell Li-Ion (2S) on 5V MCU](#double-cell-li-ion-2s-on-5v-mcu)
  * [9V Alkaline on 5V MCU](#9v-alkaline-on-5v-mcu)

<!-- tocstop -->

## How to
The library requires at least 1 analog pin (we will call this the `sense pin`) and no less than 2 bits of info on your battery: the voltage you will consider the minimum acceptable level, below which your project/product becomes unreliable and should be shut down, and the maximum voltag
