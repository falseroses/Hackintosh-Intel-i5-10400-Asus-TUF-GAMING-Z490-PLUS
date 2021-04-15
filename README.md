# Hackintosh-Intel-i5-10400-Asus-TUF-GAMING-Z490-PLUS
(Docs/photo_2021-04-15 20.48.38.png)

# Hardware
- CPU: Intel Core i5 10400
- Motherboard: Asus TUF Gaming Z490-Plus
- RAM: HyperX 32GB 3200 MHz
- iGPU: Intel UHD Graphics 630


# Working:
- [x] **Audio (through HDMI and DP too)**
- [x] **Bluetooth (via dongle)**
- [x] **Ethernet**
- [x] **iGPU (first monitor DP and second HDMI)**
- [x] **iServices**
- [x] **Shutdown/Restart**
# Not working:
- Sleep/Wake (don’t wake up the screen after sleep)
- DRM (due to iGPU)
# Not tested:
- Sidecar
- Thunderbolt
# Issue:
- iGPU second monitor works only if turn on his after login screen appears on first monitor and I can’t fix it right now.

# Tips (thanks to u/kohnor):
- Fix “F1” Startup Error:
Kernel --> Quirks --> DisableRtcChecksum = True
- Audio:
alcid=2
- iGPU Framebuffer:
(Docs/photo_2021-04-15 20.48.35.png)
