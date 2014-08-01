sqlite
======

Static iOS Library project for latest version of sqlite

To build completely capable static library, build for release on device and on simulator. Then, run the following:
```lipo -create libsqlite3.8.5-device.a libsqlite3.8.5-simulator.a -output libsqlite3.8.5.a```

Some good reading material:
http://www.sqlite.org/fts3.html
http://conedogers.wordpress.com/2014/03/02/building-sqlite-into-your-ios-applications/
