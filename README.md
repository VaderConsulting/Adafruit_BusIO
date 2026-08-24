# Adafruit_BusIO

This is a library for abstracting away UART, I2C and SPI interfacing. Original author: Adafruit. This is Dave Robinson's working copy from the Arduino `libraries` tree. Version recorded in `library.properties`: 1.11.2. Upstream: <https://github.com/adafruit/Adafruit_BusIO>.

**Source last updated:** 2022-03-01  
**Language:** C++ / Arduino  
**Target:** Arduino (*)  
**Output:** Arduino library

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Adafruit BusIO` | C++ / Arduino | library | This is a library for abstracting away UART, I2C and SPI interfacing |
| `i2c_address_detect` | C++ / Arduino | example sketch | `examples/i2c_address_detect/i2c_address_detect.ino` |
| `i2c_readwrite` | C++ / Arduino | example sketch | `examples/i2c_readwrite/i2c_readwrite.ino` |
| `i2c_registers` | C++ / Arduino | example sketch | `examples/i2c_registers/i2c_registers.ino` |
| `i2corspi_register` | C++ / Arduino | example sketch | `examples/i2corspi_register/i2corspi_register.ino` |
| `spi_modetest` | C++ / Arduino | example sketch | `examples/spi_modetest/spi_modetest.ino` |
| `spi_readwrite` | C++ / Arduino | example sketch | `examples/spi_readwrite/spi_readwrite.ino` |
| `spi_register_bits` | C++ / Arduino | example sketch | `examples/spi_register_bits/spi_register_bits.ino` |
| `spi_registers` | C++ / Arduino | example sketch | `examples/spi_registers/spi_registers.ino` |

## How to open

Install this folder as an Arduino library (Sketch → Include Library → Add .ZIP Library, or copy into `libraries/Adafruit_BusIO`). Open any `examples/*.ino` from the Arduino IDE.

## Attribution and provenance

- **Original author / maintainer:** Adafruit
- **library.properties name:** Adafruit BusIO
- **Version:** 1.11.2
- **Upstream URL:** <https://github.com/adafruit/Adafruit_BusIO>
- **Category:** Signal Input/Output
- This repository is Dave Robinson's working copy for catalogue/reference; authorship stays with the original authors.

## License

Original upstream license terms in this tree (where recorded). This repository does not claim authorship of the upstream library. See `THIRD_PARTY_NOTICES.md`. The `LICENSE` file added at import is a VaderConsulting MIT wrapper and does not replace upstream terms.
