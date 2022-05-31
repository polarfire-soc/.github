# PolarFire® SoC Embedded Software

The PolarFire SoC FPGA family delivers a combination of low power consumption,
thermal efficiency and defense-grade security for smart, connected systems.
It is the first System-on-Chip (SoC) FPGA with a deterministic,
coherent RISC-V CPU cluster and a deterministic L2 memory subsystem for
creating Linux® and real-time applications.
PolarFire SoC FPGAs span from 25K to 460K Logic Elements (LEs)
and feature 12.7 Gbps transceivers. For more information check out the PolarFire
SoC [product page](https://www.microchip.com/en-us/products/fpgas-and-plds/system-on-chip-fpgas/polarfire-soc-fpgas).

This organization is used to house the deliverables related to PolarFire SoC
embedded software and reference designs for PolarFire SoC development kits.

## Getting Started

A quick start guide is available for the PolarFire SoC Icicle Kit
[here](https://www.microsemi.com/products/fpga-soc/polarfire-soc-icicle-quick-start-guide).

The [documentation repository](https://github.com/polarfire-soc/polarfire-soc-documentation)
contains more detailed information on how to use the deliverables contained in
this organization.

## Support and Contributing

A discussion forum for the organization is available for community support,
issues, feature and enhancement requests [here](https://github.com/orgs/polarfire-soc/discussions).

For information on contributing to this project please see our
[contributing guidelines](https://github.com/polarfire-soc/polarfire-soc-documentation/blob/master/.github/CONTRIBUTING.md).

For technical support please open a tech support case using
[Microchip tech support](https://microchipsupport.force.com/s/).

Training playlists are available to help users get started using PolarFire [here](https://www.youtube.com/c/MicrochipDeveloperHelp/playlists?view=50&sort=dd&shelf_id=4).

The RISC-V Innovation Unleashed training series provides webinars describing
different aspects of PolarFire SoC and is available [here](https://www.microchip.com/en-us/education/technical-learning-center/webinars/fpga-webinars/risc-v-innovation-unleashed).

## Resources

Below is a list of the different deliverables that can be found in this
organization:

**Documentation**

- [Documentation](https://github.com/polarfire-soc/polarfire-soc-documentation):
user guides and documentation for PolarFire SoC

**Reference designs**

- [Icicle Kit Reference Design](https://github.com/polarfire-soc/icicle-kit-reference-design):
scripts to generate an FPGA reference design for the PolarFire SoC Icicle Kit

**Bare Metal Embedded Software**

- [Platform](https://github.com/polarfire-soc/platform): Hardware Abstraction Layer
(HAL) and peripheral drivers for PolarFire SoC

- [Bare Metal Examples](https://github.com/polarfire-soc/polarfire-soc-bare-metal-examples):
drivers and example projects for PolarFire SoC peripherals

**Boot Loaders**

- [Hart Software Services (HSS)](https://github.com/polarfire-soc/hart-software-services):
source code for the HSS zero stage bootloader and system monitor used in
PolarFire SoC

**Linux Build Systems**

- [PolarFire SoC Yocto BSP](https://github.com/polarfire-soc/meta-polarfire-soc-yocto-bsp):
build a Linux image for PolarFire SoC using Yocto

- [PolarFire SoC Buildroot SDK](https://github.com/polarfire-soc/polarfire-soc-buildroot-sdk):
build a Linux image for PolarFire SoC using Buildroot

**Real Time Operating Systems (RTOS)**

- [Zephyr](https://github.com/polarfire-soc/zephyr): fork
of the upstream Zephyr repository with support for PolarFire SoC

- [RTEMS](https://github.com/polarfire-soc/rtems): fork
of the upstream RTEMS repository with support for PolarFire SoC

**FPGA Build Systems**

- [Icicle Kit Bitstream Builder](https://github.com/polarfire-soc/icicle-kit-minimal-bring-up-design-bitstream-builder):
example scripted flow for a version controlled FPGA bitstream generation system
