## Will be launched soon!!!


## Executable Compatibility Notice

This executable binary was built and tested on a **Raspberry Pi Zero W** running **Raspberry Pi OS Lite (32-bit, ARMv6)**.

### Tested Environment:
* **Architecture:** ARMv6/ARMv7 (32-bit)
* **Operating System:** Raspberry Pi OS Lite (Debian-based)
* **Processor:** Broadcom BCM2835 (RPi Zero W)

**WARNING:** Due to the complexities of Linux binary distribution, this executable may or may not work on other Linux distributions (e.g., Ubuntu, Fedora) or architectures (e.g., x86/64-bit desktop) without the required libraries or different processor instruction sets. Users are encouraged to try running the binary but should be prepared to build the tool from source if compatibility issues arise.





## Build Details

This file was compiled from the Python source code (`cl-csv.py`) into a single, standalone executable using the **Nuitka** Python compiler.

* **Compiler Version:** Nuitka 2.8.9
* **Python Version:** Python 3.13
* **Build Command:**
  ```
    python3 -m nuitka --onefile --low-memory cl-csv.py
  ```

  ## Licensing & Source Code Information

### Nuitka Runtime License

This executable includes a small runtime component derived from the Nuitka compiler, which is governed by the **GNU General Public License, Version 3 (GPLv3)**.

* **A copy of the full GPLv3 and the required Nuitka Runtime Exception are provided in the accompanying `NOTICE` file.**
* The Nuitka source code repository can be found here: [https://github.com/Nuitka/Nuitka](https://github.com/Nuitka/Nuitka)
