MiTV-MZTU1 launcher preview 2.7-mztu1

APK and reproducible source bundle for the custom launcher.
Features: six-app dock; BTC, ETH, LTC in USD at upper left; Krasnoyarsk weather at upper right.
Validation: 253 unit tests passed; release build and APK signature verification passed; lint has no errors.
Not yet installed or visually verified on the actual TV. Live API responses are not yet verified.
The APK is signed with a development key. Do not disable existing Home/setup components before validation.

Upstream: https://github.com/Gathin23/cleanyourtv, revision 575d73f0f30c329aa7ebaea2bc863943fd9bf7f9.
MIT license and Outfit font license included. Custom code and build instructions are in the source ZIP.
Build: JDK 17, Android SDK 34 and build-tools 34.0.0; run launcher/gradlew.bat from tv/launcher:
gradlew.bat --no-daemon --max-workers=2 testReleaseUnitTest lintRelease assembleRelease
Verify downloads against SHA256SUMS.txt.
