# ARM Benchmakrs

### Various benchmarks used for the [ARM CPU Model](https://github.com/oumilk-performance-architecture/cpu-model).

### Prerequisites
  * [GNU Arm Embedded Toolchain](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads)

### Setup the Project
```bash
> mkdir -p /usr/local/gcc-arm
> mv ~/Downloads/gcc-arm-none-eabi-10-2020-q4-major /usr/local/gcc-arm
> echo "export PATH=$PATH:/usr/local/gcc-arm/gcc-arm-none-eabi-10-2020-q4-major/bin/" >> ~/.zprofile
```

### Acknowledgements
 * [GCC ARM Install](https://pros.cs.purdue.edu/cortex/getting-started/macOS.html) - Information on installing GCC ARM on Mac