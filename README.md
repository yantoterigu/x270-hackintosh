# OpenCore EFI for ThinkPad X270
This repository includes all EFI folders and files needed for macOS 12.5.1 Monterey. OpenCore version 0.8.3
<a href="https://github.com/BlackOtton/ThinkPad-X270-OpenCore/blob/main/README-PL.md">Polish version of README</a>
![AboutThisMac](https://user-images.githubusercontent.com/37146104/188917794-b2854301-e30c-49e6-901c-0d9e965053ef.png)



Specifications:
- **CPU**: Intel Core i5-7300U
- **GPU**: Intel HD Graphics 620
- **RAM**: 32GB DDR4
- **Storage**: NVME SSD 256Gb
- **WiFi & Bluetooth**: Intel Dual Band Wireless-AC 8265
- **Ethernet**: Intel Ethernet I219-LM
- **WWAN**: Fibocom L831-EAU (NCM)@0
- **Audio**: REALTEK ALC298

<details><summary><b>What works?</b> :white_check_mark:</summary>
    <li>Power Management <br> </li>
    <li>Power Bridge <br> </li>
    <li>Graphics Acceleration <br> </li>
    <li>Audio Output&Input <br> </li>
    <li>Touchscreen <br> </li>
    <li>USB Ports <br> </li>
    <li>WiFi <br> </li>
    <li>Bluetooth <br> </li>
    <li>Ethernet <br> </li>
    <li>Docking USB Ports <br> </li>
    <li>Docking Ethernet <br> </li>
    <li>HDMI Out <br> </li>
    <li>TouchPad (Click and gestures) <br> </li>
    <li>TrackPoint <br> </li>
    <li>Sleep <br> </li>
</details>

<details><summary><b>What doesn't work?</b> :x:</summary>
  <li>DisplayPort Out from dock (if you know how to repair this, please let me know.) <br> </li>
  <li>VGA Out from dock <br> </li>
  <li>DVI Out from dock <br> </li>
  <li>Lid Sleep <br> </li>
  <li>Sidecar <br> </li>
</details>

<details><summary><b>Problems</b> :warning:</summary>
  <li>Wi-Fi disconnets when ethernet is connected.<br> </li>
    <i>Fix: Disable "Wireless Auto Disconnection" in BIOS (Config>Network)</i>
</details>
