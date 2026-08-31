# Firmware

Images the device fetches for itself over the air, and the manifest that
names them.  Public so that a device can read it with no account and no
token: anything else would mean shipping a credential inside every unit.

`firmware.txt` is the machine-readable index; everything else here is a build.
It is generated, and the format is documented in its own header comment.

Base URL: `https://raw.githubusercontent.com/chdunkel/device-firmware/main/`

| board | kind | version | size | published as |
| --- | --- | --- | ---: | --- |
| ws43 | app | 0.9.7 | 3.6 MB | `ws43/app-0.9.7-72f87e53.bin` |
| ws43 | radio | 3.0.6 | 1.4 MB | `ws43/radio-3.0.6.bin` |
| ws43 | app | 0.9.6 | 3.3 MB | `ws43/app-0.9.6-7f29a6cb.bin` |

Only the 5 newest of each kind are kept: a device image is several
megabytes, so keeping every build would put the repository past a
gigabyte within a year and make it painful to clone.

## Boards

| id | hardware |
| --- | --- |
| `ws43` | Waveshare ESP32-P4-WIFI6-Touch-LCD-4.3 |
