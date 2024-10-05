# Pico audio maker

TODO: Add description

![./Exports-v1.1/Top.svg](./Exports-v1.1/Top.svg)
![./Exports-v1.1/Bottom.svg](./Exports-v1.1/Bottom.svg)

TODO: Add photo of completed board

## Block diagram

```mermaid
graph TD
    A[<a href="https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html">Raspberry Pi Pico</a>] --> |I2S| B[<a href="https://www.digikey.com.au/en/products/detail/analog-devices-inc-maxim-integrated/MAX98357AETE-T/4936122">MAX98357AETE+T</p>]
    B -->| | C[Header for speaker]
    A -->|?????| D[Might add some LEDs in the future]
```

## Licence

Copyright © 2024 Phil Baldwin

This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.

You should have received a copy of the license along with this work. If not, see <http://creativecommons.org/licenses/by-sa/4.0/>.
