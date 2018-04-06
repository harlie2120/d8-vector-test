# d8-vector-test
Project to reproduce vector drawable bugs on ARM-v7a devices with Android API 19 and below when using d8 compiler.

How to use
----------
Modify gradle.properties and set:
- `android.enableD8=true` to use d8 compiler, vector image will be broken on Android API 19 and below.
- `android.enableD8=false` to use dx compiler, vector image will be displayed properly.
