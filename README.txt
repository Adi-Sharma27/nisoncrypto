NISONCRYPTO ANDROID APK PACKAGE
=============================

1. TAB 1 (CHAT EVALUATOR) PARTITIONS:
   - Section 1: Active Market & Signal Status (Live Price, Candle Pattern, Trend & RSI, Floor/Ceiling & Volume)
   - Section 2: Trade Verdict Chat (Plain-English CALL / PUT / WAIT cards with Timing, Entry, Target, Stop Loss)
   - Section 3: Ask About Your Call or Put Trade (Quick chips + prompt input)

2. TAB 2 (LIVE CHART) PARTITIONS:
   - Section 1: Pair & Timeframe Controls (10 pairs, 1m to 1d)
   - Section 2: Candlestick Chart, EMA & Trade Zones (Candles, EMA 9/21, Entry/Target/Stop lines, Crosshair)
   - Section 3: Chart Pattern & Support/Resistance Breakdown

3. HOW TO BUILD THE APK:
   - Option A (GitHub Actions): Push this project to a GitHub repository; the workflow in
     .github/workflows/build-apk.yml automatically builds app-debug.apk and uploads it as an artifact.
   - Option B (Local Android Studio):
     1. Run `npm install`
     2. Run `npx cap add android` and `npx cap sync android`
     3. Open the `android` folder in Android Studio and select Build -> Build Bundle(s) / APK(s) -> Build APK(s).
