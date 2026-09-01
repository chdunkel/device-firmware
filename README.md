# Firmware

Images the device fetches for itself over the air, and the manifest that
names them.  Public so that a device can read it with no account and no
token: anything else would mean shipping a credential inside every unit.

`firmware.txt` is the machine-readable index; everything else here is a build.
It is generated, and the format is documented in its own header comment.

Base URL: `https://raw.githubusercontent.com/chdunkel/device-firmware/main/`

| board | kind | version | size | published as |
| --- | --- | --- | ---: | --- |
| ws43 | app | 0.9.15 | 3.6 MB | `ws43/app-0.9.15-5618d57a.bin` |
| ws43 | app | 0.9.14 | 3.6 MB | `ws43/app-0.9.14-c0c89eeb.bin` |
| ws43 | app | 0.9.13 | 3.6 MB | `ws43/app-0.9.13-4db4415e.bin` |
| ws35 | app | 0.9.12 | 2.8 MB | `ws35/app-0.9.12-35e3aa2b.bin` |
| ws43 | app | 0.9.12 | 3.6 MB | `ws43/app-0.9.12-9e4a11e8.bin` |
| ws43 | app | 0.9.11 | 3.6 MB | `ws43/app-0.9.11-42ef9d33.bin` |
| ws43 | radio | 3.0.6 | 1.4 MB | `ws43/radio-3.0.6.bin` |

Only the 5 newest of each kind are kept: a device image is several
megabytes, so keeping every build would put the repository past a
gigabyte within a year and make it painful to clone.

## Boards

| id | hardware |
| --- | --- |
| `ws35` | Waveshare ESP32-S3-Touch-LCD-3.5B |
| `ws43` | Waveshare ESP32-P4-WIFI6-Touch-LCD-4.3 |
