# Firmware

Images the device fetches for itself over the air, and the manifest that
names them.  Public so that a device can read it with no account and no
token: anything else would mean shipping a credential inside every unit.

`firmware.txt` is the machine-readable index; everything else here is a build.
It is generated, and the format is documented in its own header comment.

Base URL: `https://raw.githubusercontent.com/chdunkel/device-firmware/main/`

| board | kind | version | size | published as |
| --- | --- | --- | ---: | --- |
| ws43 | app | 0.9.18 | 3.8 MB | `ws43/app-0.9.18-3dc18df7.bin` |
| ws43 | app | 0.9.17 | 3.8 MB | `ws43/app-0.9.17-275aa713.bin` |
| all | trackdb | 1788385359 | 1.9 MB | `all/trackdb-1788385359-9db664a2.pltdb` |
| ws43 | app | 0.9.15 | 3.6 MB | `ws43/app-0.9.15-5618d57a.bin` |
| ws43 | app | 0.9.14 | 3.6 MB | `ws43/app-0.9.14-c0c89eeb.bin` |
| ws43 | app | 0.9.13 | 3.6 MB | `ws43/app-0.9.13-4db4415e.bin` |
| ws35 | app | 0.9.12 | 2.8 MB | `ws35/app-0.9.12-35e3aa2b.bin` |
| ws43 | radio | 3.0.6 | 1.4 MB | `ws43/radio-3.0.6.bin` |
| all | map | 85156404 | 0.6 MB | `all/maps/ALBACETE_CIRCUITO.PLM` |
| all | map | 0CC12BEC | 1.6 MB | `all/maps/ALBI_CIRCUIT.PLM` |
| all | map | F26DA4E2 | 1.3 MB | `all/maps/ALCARRAS_CIRCUITO.PLM` |
| all | map | 5D6BA755 | 0.6 MB | `all/maps/ALES_CIRCUIT-VITESSE.PLM` |
| all | map | 1710477F | 1.8 MB | `all/maps/ALMERIA_CIRCUITO.PLM` |
| all | map | A2803E8B | 1.1 MB | `all/maps/ANNEAU-DU-RHIN_3-0-KM.PLM` |
| all | map | 259D48CC | 1.8 MB | `all/maps/ANNEAU-DU-RHIN_3-7-KM.PLM` |
| all | map | DA659E83 | 1.8 MB | `all/maps/ANNEAU-DU-RHIN_GRAND-ANNEAU.PLM` |
| all | map | 75832174 | 4.2 MB | `all/maps/ASCARI_FULL-CIRCUIT.PLM` |
| all | map | 612BB31D | 4.2 MB | `all/maps/ASSEN_GP.PLM` |
| all | map | D399DFA7 | 1.0 MB | `all/maps/AUTODROMO-DI-MODENA_CIRCUITO.PLM` |
| all | map | 4B1790B3 | 0.2 MB | `all/maps/BARBER-MOTORSPORTS-P_FULL-COURSE.PLM` |
| all | map | 8145E0E9 | 2.2 MB | `all/maps/BILSTER-BERG_GESAMTSTRECKE.PLM` |
| all | map | 9F868656 | 1.0 MB | `all/maps/BRAGA_CIRCUITO.PLM` |
| all | map | 1D19E0F3 | 0.6 MB | `all/maps/BRESSE_GP.PLM` |
| all | map | 0520F838 | 2.7 MB | `all/maps/CALAFAT_CIRCUITO.PLM` |
| all | map | D0F4CBC6 | 2.1 MB | `all/maps/CASTELLOLI_CIRCUITO.PLM` |
| all | map | 3EB9B3E7 | 3.3 MB | `all/maps/CATALUNYA_GP.PLM` |
| all | map | 81ADF806 | 2.3 MB | `all/maps/CHARADE_CIRCUIT.PLM` |
| all | map | 315AF9CF | 0.4 MB | `all/maps/CHENEVIERES_CIRCUIT.PLM` |
| all | map | 5F347DA5 | 0.3 MB | `all/maps/CIRCUIT-OF-THE-AMERI_FULL-COURSE.PLM` |
| all | map | F82F6BE8 | 0.4 MB | `all/maps/CROIX-EN-TERNOIS_CIRCUIT.PLM` |
| all | map | 20CDDEC9 | 0.4 MB | `all/maps/DAYTONA-ROAD-COURSE_FULL-COURSE.PLM` |
| all | map | 0B2393E9 | 2.0 MB | `all/maps/DIJON-PRENOIS_GP.PLM` |
| all | map | 64D94DF8 | 0.9 MB | `all/maps/ESTORIL_GP.PLM` |
| all | map | 82BBBD03 | 2.1 MB | `all/maps/FUJI-SPEEDWAY_FULL-COURSE.PLM` |
| all | map | 15B273DE | 3.4 MB | `all/maps/HOCKENHEIMRING_GP-KURS.PLM` |
| all | map | 113E05E6 | 1.9 MB | `all/maps/IMOLA_GP.PLM` |
| all | map | B778EF63 | 0.2 MB | `all/maps/INDIANAPOLIS-ROAD-CO_FULL-COURSE.PLM` |
| all | map | 06F596E2 | 1.5 MB | `all/maps/JARAMA_CIRCUITO.PLM` |
| all | map | 1F5B74FD | 1.9 MB | `all/maps/JEREZ_GP.PLM` |
| all | map | EF2D96D8 | 0.2 MB | `all/maps/LAGUNA-SECA_FULL-COURSE.PLM` |
| all | map | 2C46FC34 | 1.5 MB | `all/maps/LAUSITZRING_GRAND-PRIX-STRECKE.PLM` |
| all | map | B3991434 | 1.8 MB | `all/maps/LE-MANS-BUGATTI_BUGATTI.PLM` |
| all | map | 39BF66A9 | 0.8 MB | `all/maps/LEDENON_CIRCUIT.PLM` |
| all | map | 60CDD601 | 0.3 MB | `all/maps/LIME-ROCK-PARK_FULL-COURSE.PLM` |
| all | map | C0BC5CD7 | 1.6 MB | `all/maps/MAGNY-COURS_GRAND-PRIX.PLM` |
| all | map | 4CDC5952 | 0.4 MB | `all/maps/METTET_CIRCUIT-JULES-TACHEN.PLM` |
| all | map | C5C67F87 | 2.2 MB | `all/maps/MISANO_CLOCKWISE.PLM` |
| all | map | 3BFEA06A | 1.7 MB | `all/maps/MONTEBLANCO_CIRCUITO.PLM` |
| all | map | F87D474A | 0.6 MB | `all/maps/MOTEGI_FULL-COURSE.PLM` |
| all | map | DE950867 | 2.2 MB | `all/maps/MOTORLAND-ARAGON_GP-FIA.PLM` |
| all | map | D05CFC55 | 1.9 MB | `all/maps/MUGELLO_GP.PLM` |
| all | map | 4EACD272 | 2.2 MB | `all/maps/NAVARRA_CIRCUITO.PLM` |
| all | map | F95A9D65 | 1.0 MB | `all/maps/NOGARO_CIRCUIT-PAUL-ARMAGNA.PLM` |
| all | map | 33E0D261 | 3.6 MB | `all/maps/NURBURGRING_GESAMTSTRECKE-24H.PLM` |
| all | map | 72165AC2 | 3.6 MB | `all/maps/NURBURGRING_GESAMTSTRECKE-NLS.PLM` |
| all | map | 0A7D4F17 | 2.5 MB | `all/maps/NURBURGRING_GP-STRECKE.PLM` |
| all | map | 8F5341E9 | 4.2 MB | `all/maps/NURBURGRING_NORDSCHLEIFE-TOURIST.PLM` |
| all | map | 86CF35BA | 1.8 MB | `all/maps/NURBURGRING_SPRINTSTRECKE.PLM` |
| all | map | C1F101FF | 1.0 MB | `all/maps/OKAYAMA_FULL-COURSE.PLM` |
| all | map | EC1EC5C2 | 1.5 MB | `all/maps/PAU-ARNOS_CIRCUIT.PLM` |
| all | map | 9E925855 | 2.2 MB | `all/maps/PAUL-RICARD_3-8-KM-3C-MISTRAL-CH.PLM` |
| all | map | DCA97E8C | 2.9 MB | `all/maps/PAUL-RICARD_5-8-KM-1C-V2-MISTRAL.PLM` |
| all | map | D4DD698D | 1.0 MB | `all/maps/PORTIMAO_GP.PLM` |
| all | map | 1496280F | 1.9 MB | `all/maps/RED-BULL-RING_GP.PLM` |
| all | map | EC6191DB | 1.3 MB | `all/maps/RICARDO-TORMO_GP.PLM` |
| all | map | 164719BE | 0.4 MB | `all/maps/ROAD-AMERICA_FULL-COURSE.PLM` |
| all | map | FB9ECDC9 | 0.5 MB | `all/maps/ROAD-ATLANTA_FULL-COURSE.PLM` |
| all | map | 73D10CC4 | 0.7 MB | `all/maps/SACHSENRING_GP-KURS.PLM` |
| all | map | 7D228343 | 0.3 MB | `all/maps/SEBRING_FULL-COURSE.PLM` |
| all | map | 954E84FB | 0.2 MB | `all/maps/SONOMA-RACEWAY_FULL-COURSE.PLM` |
| all | map | 56CF50E0 | 2.5 MB | `all/maps/SPA-FRANCORCHAMPS_GP.PLM` |
| all | map | 0CFDB377 | 0.6 MB | `all/maps/SPORTSLAND-SUGO_FULL-COURSE.PLM` |
| all | map | 70152C05 | 2.5 MB | `all/maps/SUZUKA_FULL-COURSE.PLM` |
| all | map | AC652BA3 | 1.5 MB | `all/maps/SYDNEY-MOTORSPORT-PA_FULL-COURSE.PLM` |
| all | map | 045B42E1 | 0.9 MB | `all/maps/TOR-POZNA_CIRCUIT.PLM` |
| all | map | C05DE7F7 | 0.2 MB | `all/maps/TSUKUBA_FULL-COURSE.PLM` |
| all | map | 785170B0 | 0.9 MB | `all/maps/VAL-DE-VIENNE_CIRCUIT.PLM` |
| all | map | 54E8FD22 | 0.9 MB | `all/maps/VARANO_CIRCUITO.PLM` |
| all | map | 5C37140A | 0.7 MB | `all/maps/VIRGINIA-INTERNATION_FULL-COURSE.PLM` |
| all | map | 5334EDCD | 0.4 MB | `all/maps/WATKINS-GLEN_FULL-COURSE.PLM` |
| all | map | 6AFC250A | 2.1 MB | `all/maps/ZANDVOORT_GP.PLM` |
| all | map | ADB98A72 | 1.9 MB | `all/maps/ZOLDER_CIRCUIT.PLM` |

Only the 5 newest of each kind are kept: a device image is several
megabytes, so keeping every build would put the repository past a
gigabyte within a year and make it painful to clone.

## Boards

| id | hardware |
| --- | --- |
| `ws35` | Waveshare ESP32-S3-Touch-LCD-3.5B |
| `ws43` | Waveshare ESP32-P4-WIFI6-Touch-LCD-4.3 |
