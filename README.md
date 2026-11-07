# AONE IP CONNECT Vicky Edition

Android Java starter project with:
- AONE IP CONNECT screen and custom launcher vector logo.
- In-app footer watermark: VICKY SANDHU • 9023020046.
- Local IPv4 subnet discovery for /24 through /30.
- TCP probes for common device ports.
- Browser launch for detected HTTP/HTTPS web interfaces.
- Manual IPv4 entry and copy IP.

## Build
1. Open this folder in Android Studio.
2. Install Android SDK Platform 35 and use JDK 17.
3. Sync Gradle.
4. Run on a phone connected to the same LAN.
5. Build > Build Bundle(s) / APK(s) > Build APK(s).

The APK is not precompiled in this source ZIP.

## Limitations
This is best-effort TCP discovery, not exhaustive device identification. It does not yet implement ONVIF, SNMP, mDNS, SSDP, RTSP playback, MAC/vendor lookup or credential storage. A device with blocked ports may not show. Only scan networks you own or are authorized to administer.
