SparkFun GPS-RTK Dead Reckoning pHAT (ZED-F9R) for Raspberry Pi
========================================

[![SparkFun GPS-RTK Dead Reckoning pHAT (ZED-F9R) for Raspberry Pi](https://cdn.sparkfun.com/r/600-600/assets/parts/2/1/0/9/6/21305-GPS-RTK-Dead-Reckoning-pHAT-Feature.jpg)](https://www.sparkfun.com/products/21305)

[*SparkFun GPS-RTK Dead Reckoning pHAT (ZED-F9R) for Raspberry Pi (GPS-21305)*](https://www.sparkfun.com/products/21305)

The SparkFun ZED-F9R GPS pHAT is a high precision, sensor fusion GPS board with equally impressive configuration options and takes advantage of u-blox's Automotive Dead Reckoning (ADR) technology. The ZED-F9R module provides a highly accurate and continuous position by fusing a 3D IMU sensor, wheel ticks, a vehicle dynamics model, correction data, and GNSS measurements.

The ZED-F9R module is an 184-channel u-blox F9 engine GNSS receiver, meaning it can receive signals from the GPS, GLONASS, Galileo, and BeiDou constellations with ~0.01-meter accuracy! That's right, such accuracy can be achieved with an RTK navigation solution when used with a correction source. Note that the ZED-F9R can only operate as a rover, so you will need to connect to a base station. The module supports the concurrent reception of four GNSS systems. The combination of GNSS and integrated 3D sensor measurements on the ZED-F9R provides accurate, real-time positioning rates of up to 30Hz.

This pHAT maximizes position accuracy in dense cities or covered areas compared to other GPS modules. Even under poor signal conditions, continuous positioning is provided in urban environments and available during complete signal loss (e.g., short tunnels and parking garages). The ZED-F9R is the ultimate solution for autonomous robotic applications that require accurate positioning under challenging conditions.

This u-blox receiver supports a few serial protocols. By default, we used the Raspberry Pi's serial UART to communicate with the module. With pre-soldered headers, no soldering is required to stack the pHAT on a Raspberry Pi, NVIDIA Jetson Nano, Google Coral, or any single-board computer with the 2x20 form factor. We have also broken out a few 0.1"-spaced pins from the u-blox receiver. A Qwiic connector is also added if you need to connect a Qwiic-enabled device.

U-blox-based GPS products are configurable using the popular but dense Windows program u-center. Many different functions can be configured on the ZED-F9R: baud rates, update rates, geofencing, spoofing detection, external interrupts, SBAS/D-GPS, etc.

The SparkFun ZED-F9R GPS pHAT also has an onboard rechargeable battery that provides power to the RTC on the ZED-F9R. This reduces the time-to-first fix from a cold start (~24s) to a hot start (~2s). The battery will maintain RTC and GNSS orbit data without being connected to power for plenty of time.

Repository Contents
-------------------

* **/Documentation** - Data sheets, additional product information
* **/Hardware** - Eagle design files (.brd, .sch)
* **/Production** - Production panel files (.brd)

Documentation
--------------
* **[Library](https://github.com/sparkfun/Qwiic_Ublox_Gps_Py)** - Python library for the ZED-F9R.
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/1172)** - Basic hookup guide for the ZED-F9R.

Product Versions
----------------
* [GPS-21305](https://www.sparkfun.com/products/21305)
* [GPS-16475](https://www.sparkfun.com/products/16475)

Version History
---------------
* [v1.1](https://github.com/sparkfun/SparkFun_GPS_Dead_Reckoning_PHat_ZED-F9R/releases/tag/v1.1)
* [v1.0](https://github.com/sparkfun/SparkFun_GPS_Dead_Reckoning_PHat_ZED-F9R/releases/tag/v1.0) - Initial Release

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.

_<COLLABORATION CREDIT>_
