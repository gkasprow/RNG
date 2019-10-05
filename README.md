# RNG
5Gbit/s Random Number Generator

It is simple random number generator based on 20mA Zener diode. It is supplied from 12V.
The Zener is biased with 24V/20mA and generates white noise up to 2GHz.
The noise is amplified and fed to fast CML comparator and then to the SATA cable.
The whiteband noise is also available on the SMA output. The level is roughly 0dBm.
The project is based on EDN article: https://www.edn.com/design/test-and-measurement/4358938/Zener-diode-and-MMICs-produce-true-broadband-noise
