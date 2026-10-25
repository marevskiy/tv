MiTV-MZTU1 launcher preview 2.7-mztu1.1 (versionCode 10)

Current APK: MiTV-MZTU1-2.7-mztu1.1.apk
Current source: MiTV-MZTU1-source-2.7-mztu1.1.zip

Six dock apps: Vokino, SmartTube, Kinopoisk, VK Video, Kick, VLC.
BTC/ETH/LTC prices in USD at upper left; Krasnoyarsk weather at upper right.
New: automatic 3840x2160 nature wallpapers from six Unsplash landscapes, changing every hour while Home is visible.
Last two photos cached; downloads and decoding bounded; no background service.
The Wallpaper picker can disable nature (None) or resume it (Theme default).
Failed feeds retry in 5 minutes; improved weather timeouts and error diagnostics.

Validation: 269 tests passed, 0 failures/errors/skips; lint 0 errors; release build and signature verified.
Same development signing certificate as preview 2.7-mztu1, so pm install -r upgrades it.
All six source photographs were downloaded and verified at 3840x2160; Java download client also exercised live.
Previous preview was installed and visually checked on the TV: dock and live quotes worked; weather was unavailable.
Open-Meteo responds successfully on Windows and in cloud Java tests. Root cause of the TV weather failure is not yet established.
This new version still requires on-device installation, wallpaper/weather checks, and an actual screenshot.
Keep stock Home/setup components enabled pending safe handover and backup/restore checks.

Sources derive from https://github.com/Gathin23/cleanyourtv at 575d73f0f30c329aa7ebaea2bc863943fd9bf7f9.
MIT and Outfit font licenses included. Photos download at runtime; Unsplash license: https://unsplash.com/license
Build requirements and commands are in tv/README.md inside the source ZIP.
SHA256SUMS.txt covers all APK/source bundles in this branch; older previews remain available.
