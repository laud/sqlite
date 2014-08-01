sqlite
======

Static Library project for latest version of sqlite

To build completely capable static library, build for release on device and on simulator. Then, run the following:
```lipo -create libsqlite3.8.5-device.a libsqlite3.8.5-simulator.a -output libsqlite3.8.5.a```
