# HP-Pavilion-15-cs0xxx-Hackintosh
EFI for HP Pavilion 15 cs0xxx for Hackintosh Sonoma-Sequoia


# Specs

| Component  | Detail |
| ------------- | ------------- |
| Product Name  | HP Pavilion - 15-cs0003no |
| CPU  | Intel(R) Core(TM) i7-8550U 2GHz  |
| iGPU  | Intel UHD Graphics 620 |
| dGPU  | NVIDIA GeForce MX150 2GB (Disabled through -wegnoegpu) |
| RAM   | 8GB DDR4 2400MHz (2x4) |
| Storage  | M.2 256GB SSD Toshiba KBG30ZMV256G |
| WIFI & Bluetooth  | Intel Dual Band Wireless-AC7265 |
| Ethernet  | Realtek RTL8111 GbE |
| Keyboard  | HP Standard PS/2 Keyboard full-sized (With Fn keys) |
| Trackpad  | HP ELAN Clickpad  |
| Camera  | HP IR Camera / HP Wide Vision FHD Camera |
| Microphone  | Realtek(Audio) |
| Sound controller  | Realtek Audio ALC295 |
| External Ports  | 2 USB 3.1 Gen 1; HDMI 1.4; 1 Headphone/Microphone combo; 1 USB 3.1 Type-C Gen 1 |
| Expantion Ports  | 1 multi-format SD media card reader |
| Mac SMBios  | MacBookPro16,3 |



# Tecnical

* What works
  * iGPU
  * Trackpad (With gestures)
  * Keyboard with FN Keys (F12, F4 and F1 doesn't work)
  * All USB ports
  * Wifi Card (Only up to Sonoma, for Sequoia change the wifi Kext for Itlwm.kext + HeliPort)
  * Bluetooth
  * In-built Microphone
  * Battery
  * Ethernet
  * Sleep
  * Wake on Lid

* What doesn't work
  * In-build Camera
  * Speakers
  * HP IR Camera (This might be the cause why the camera itself doesn't work)

* Haven't tested yet
  * Continuity services
  * Jack audio
  * HDMI
 

# Before you use it

Before you use this EFI, remember to use [GenSMBios](https://github.com/corpnewt/GenSMBIOS) to generate the SMBios. For now I used the MacBookPro16,3 but I will be testing with more in the future.
