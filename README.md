# airgpu
## VM Settings
* L4 or L40S (for gaming drivers and DLSS 3)
* 150 GB SSD
*  1080p / 15 Mbits/secs
## Host
### First boot
* Update GPU Driver:  Select Gaming
* cmd

   ```"C:\program files\sunshine\sunshine.exe" --creds user 5WUu2mpTl6xe```
### Nvidia control
* Shader Cache: 10 GB
* vsync: on (turn off in game)
* Low latency: Ultra
* power management: Prefer maximum
### Sunshine/vibeshine
* Capture Method: Windows Graphics Capture (WGC) variable
* Force a specific encoder:  NVIDIA NVENC
* NVENC Encoder: Performance Preset: P4
### GOG Galaxy
* https://webinstallers.gog-statics.com/download/GOG_Galaxy_2.0.exe
### Reshade
*  https://reshade.me/
### Vortex
* https://api.nexusmods.com/vortex/download

## Moonlight client
* https://github.com/moonlight-stream/moonlight-qt/releases
  * portable x64
* Start from start menu
* 1080p / 60 fps
* Bitrate:
  * airgpu recommends 15 Mbits/sec
  * AI recommends 20-25 Mbits/sec
  * network connection 100Mbits / sec
* VSync:
  * off for lower latency
  * on with frame pacing for mid latency but no tearing
* Advanced
  * Video decoder: force hardware
  * Video Codec: AV1
  * Automatically find PC on network: off

