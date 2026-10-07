# Alpine Ai-NET interface library for ESP32 and Arduino

An easy-to-use interface library to facilitate access to Alpine's Ai-NET

## Purpose

The goal of this library is to help developers and makers communicate with their Alpine gear. This library typically requires one pin to transmit and one pin to receive the bus state, although Arduino's with the comparator may have 2 pins that serve as both functions.

Technical information on how Ai-NET works and how to interface with it can be found on the [electrical](docs/electrical.md) and [signalling](docs/signalling.md) pages (once they exist).

## Progress

### ESP32
* Support for ESP32's with the RMT peripheral - To be done
* Documentation for the above - To be done
* Example code for the aboveT - To be done
* Add support for PlatformIO Registry - To be done

### Arduino
* Support for Arduinos and compatibles - To be done
* Documentation for the above - To be done
* Example code for the above- To be done
* Add support for Arduino Library Manager - To be done

### General
* Document electrical and signalling pages - To be done

## Contributing

Code contributions are welcome as pull requests. Bugs can go into the usual `Issues` space.

## Credits

Nik1976 from the [Ai10](https://groups.google.com/g/proj-ai10) project for providing basic protocol and Arduino code samples.
V Vasin for sanity checks and testing.

## License

This code is released with the GNU GPLv3 license. Please see `LICENSE` for more information.

## Disclaimer and Copyright

All code within this file was developed privately by monitoring communication
on an Ai-NET bus between an Alpine head unit and various Alpine devices.

Alpine (or any parent or subsidiary) do not support this code in any way.
They did not contribute to or endorse it. *Do not pester them for support.*
This work is provided "as-is" without any express or implied warranty.

Ai-NET is a trademark of Alps Alpine Co., Ltd.
Alpine aka Alpine Electronics, Inc. is a subsidiary of Alps Alpine Co., Ltd.
All other trademarks are the property of their respective owners.
