# Ada/WebAssembly Android Demo application

This is small example of an Android application written in Ada
and compiled with [gnat-llvm](https://github.com/godunko/adawebpack)
to run inside WebView component.

## Building

Just run
```
./gradlew assembleDebug
```

Resulting APK is `./app/build/outputs/apk/debug/app-debug.apk`.
