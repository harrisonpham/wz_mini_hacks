# Selfhosting notes

## QR Scan Provisioning

https://codepen.io/ril3y/full/gXyzmO/

## Settings

| key | description | values |
|-----|-------------|--------|
| nightVision | Enable IR | 1 = on, 2 = off, 3 = auto |
| night_led_ex | IR type? | 1 = near, 2 = far |
| night_cut_thr | IR threshold | 1 = 'dusk mode', 2 = 'dark mode' |
| indicator | Camera LED status lights | 1 = on, 2 = off |
| verSwitch | Flip vertically | 1 = no flip, 2 = flip |
| horSwitch | Flip horizontally | 1 = no flip, 2 = flip |
| osdSwitch | Show timestamp | 1 = show, 2 = hide |
| watermark_flag | Show wyze logo | 1 = show, 2 = hide |
| AST | Audio recording | 1 = on, 2 = off |
| recordType | Record to SD card | 1 = continuous, 2 = events only, 3 = no recording |
| MASwitch | Record when motion detected | 1 = enable, 2 = disable |
| AASwitch | Record when audio detected | 1 = enable, 2 = disable |
| SASwitch | Record when smoke alarm detected | 1 = enable, 2 = disable |
| CASwitch | Record when CO alarm detected | 1 = enable, 2 = disable |
| AMALevel | Sound detection sensitivity | 2 through 254, higher is more sensitive |
| MMALevel | Motion detection sensitivity | 2 through 254, higher is more sensitive |
| drawBoxSwitch | Draw the green boxes around objects | 1 = enable, 2 = disable |

## Stock Firmware

Also available in the `fw/` dir.

- https://download.wyzecam.com/firmware/v3/demo_wcv3_4.36.9.139.zip (works well)
- https://download.wyzecam.com/firmware/rtsp/demo_v3_RTSP_4.61.0.1.zip (stock RTSP)

## Reference links

- https://github.com/gtxaspec/wz_mini_hacks/discussions
- https://leo.leung.xyz/wiki/Wyze_Cam
- https://web.archive.org/web/20230511025605/https://leo.leung.xyz/wiki/Wyze_Cam
