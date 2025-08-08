Android app project: Quotex Signals

What this contains:
- A minimal Android Studio project (Kotlin) that polls Binance public API every 20s,
  computes EMA crossover + RSI + ATR checks locally on-device, and displays BUY/SELL/NO_SIGNAL per symbol.

How to build APK:
1. Download and open this folder in Android Studio (choose "Open an existing project").
2. Let Gradle sync and download dependencies.
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. Locate the generated APK under `app/build/outputs/apk/debug/app-debug.apk`.

Notes:
- This app uses internet access to fetch Binance klines. Ensure device has network.
- The app is a signal-only tool; it does not place trades.
- Test on demo accounts before using signals with real money.
