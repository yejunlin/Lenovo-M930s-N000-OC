# Lenovo m930s-n000 Hackintosh

## macOS version
12.4

## OC version
0.7.7

## PC Configuration
CPU: i7 10700

iGPU: UHD630

eGPU: None

Mother Board: Q470

RAM: Samsung 8G 2933MHz DDR4

Ethernet: Intel 1219

NVMe SSD: Hynix PC711

SATA HDD: WD WD10EZEX

Wireless: Realtek 8822CE

Audio: Realtek ACL623

## Known Issues
No driver for Wireless (so no Airdrop/Handoff etc...)

Bluetooth

Hynix PC711 kernel panic (disabled by DTSL)

VGA output

## What works
HDMI and DP dual display

All USB ports

Audio input and ouput

## Not test yet
DVI port

Audio-headphone jack/microphone jack

HDMI audio output

DP audio ouput

## Note
Please gen your own SMBIOS before boot and install!!! Its blank now (And add -v in boot-args if you need)

