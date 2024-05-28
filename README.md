# macOS Sonoma on Dell Latitude E7470 (OpenCore)

A work in progress EFI folder for installing macOS Sonoma on Dell Latitude E7470 using OpenCore

## Current configuration

- macOS: Sonoma 14.0
- OpenCore: 0.9.5

<summary><strong>My Hardware</strong></summary>
</br>

| Model              | Dell Latitude E7470                        |
|:-------------------|:-------------------------------------------|
| Processor          | Intel Core i7-6600U                        |
| Graphics           | Integrated Intel HD Graphics 520           |
| Memory             | 24GB DDR4 (1 x 16 + 1 x 8)                 |
| Display            | 14" FHD (1920x1080)                        |
| Storage            | NVMe SSD 500G                              |
| WLAN + Bluetooth   | Intel 8250NGW                              |
| Camera             | 1920x1080 FHD Webcam                       |
| Fingerprint Reader | Yes                                        |
| Soundcard          | Realtek ALC293                             |
| Keyboard           | Backlit Keyboard                           |
| Trackpad           | ALPS Touchpad                              |

<summary><strong>What's working</strong></summary>

- [x] Intel HD 520 Graphics `incuding graphics acceleration`
- [x] All USB ports
- [x] WiFi
- [x] Shutdown/ Reboot/ Sleep/ Wake
- [x] Intel Gigabit Ethernet
- [x] Keyboard and Trackpad(two finger vertical swipes)

<summary><strong>What's not working</strong></summary>

- [ ] Speakers and headphones jack

<summary><strong>Still to test</strong></summary>

- [ ] Internal camera
- [ ] AirDrop
- [ ] Bluetooth
- [ ] iServices
- [ ] SD Card Reader
