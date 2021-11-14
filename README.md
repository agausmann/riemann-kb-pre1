# Riemann

A pseudo-split 60% ortholinear keyboard.

## Main Features

- 60 keys in a 5x12 grid

- Supports MX-style switches

- Per-key RGB

- Hot-swappable

- QMK support (TODO)

## Design

- Designed with the features that I want, with no compromises.

- Designed to be factory-assembled, _not_ hand-soldered (I want to be able to rely on this, and I don't trust my soldering skills _that_ much).

- Microcontroller is selected to be compatible with the [Rust] programming 
language (unfortunately it does not have good support for AVR)

- PRETTY COLORS (RGB LEDs are based on the APA102 IC for that sweet, sweet
dynamic range, compared to WS2812)

[Rust]: https://rust-lang.org