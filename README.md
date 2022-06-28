# Lenovo-m930t-n000-hackintosh AKA m930s

## macOS version
12.4

## OC version
0.77

## PC Configuration
CPU: i7 10700

iGPU: UHD630

eGPU: None

Mother Board: Q470

Ethernet: Intel 1219

NVMe SSD: Hynix PC711

SATA HDD: WD WD10EZEX

Wireless: Realtek 8822CE

## Issues
Need to unplug and plug in HDMI after hybernation

No driver for Wireless (so no Airdrop/Handoff etc...)

Bluetooth

Hynix PC711 kernel panic (disabled by DTSL)

To be add...

VGA port not working

## What works
HDMI and DP dual display

All USB ports

## Not test yet
DVI port

Audio-headphone jack/microphone jack

Audio-HDMI output

Audio-DP-ouput

## Note
Please gen your own SMBIOS before boot and install!!! Its blank now (And add -v in boot-args if you need)

