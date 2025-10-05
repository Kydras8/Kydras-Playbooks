# Mobile Ops — Rapid Triage

## TL;DR
`ash
apktool d sample.apk -o out && jadx-gui out/*.dex
`",
  ",
  
1. Unpack APK / IPA as applicable.
2. Check signing & intents.
3. Note interesting endpoints.