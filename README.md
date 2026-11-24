> [!NOTE]
> **Unofficial patch branch** (`lsm6dsv-aux-mag`), not affiliated with or supported by SlimeVR.
> It adds working support for a magnetometer on the LSM6DSV auxiliary I2C bus (e.g. QMC6309 on
> LSM6DSV breakout modules with jumpers 5-8 bridged) and fixes magnetometer calibration failing
> with NaN. The changes were made with AI assistance and are tested only on a ProMicro stacked
> SPI tracker with an LSM6DSV + QMC6309 module. Use at your own risk.
> Builds: see the Actions tab of this fork (`SlimeNRF_ProMicro_Stacked_SPI_Tracker`).

# Tracker firmware for SlimeNRF
Firmware for Nordic nRF52 / nRF54L Series SoC.

Please see https://docs.slimevr.dev/smol-slimes for more information and usage.

## Hardware
- https://github.com/SlimeVR/SlimeVR-Tracker-nRF-PCB
- https://oshwlab.com/sctanf/slimenrf3

## License
Unless otherwise specified, all code in this repository is dual-licensed under either:

- MIT License ([LICENSE-MIT](LICENSE-MIT) or https://opensource.org/license/mit/)
- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or https://opensource.org/license/apache-2-0/)

at your option. This means you can select the license you prefer!

Unless you explicitly state otherwise, any contribution intentionally submitted for
inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual
licensed as above, without any additional terms or conditions.
