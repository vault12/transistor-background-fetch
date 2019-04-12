Transistor Background Fetch
===========================================================================

Forked from [https://github.com/transistorsoft/transistor-background-fetch/]()

Modified to force reload app only if device is locked.

To build this lib and update `.aar` package bundled in `cordova-plugin-background-fetch` cordova plugin, follow the next steps:

* Open `./android/tsbackgroundfetch/build.gradle` and update path to `cordova-plugin-background-fetch` working copy setting on line 80:

```
def cordovaDir = "/Users/me/vault12/cordova-plugin-background-fetch"
```

* Open `./android/tsbackgroundfetch/` folder in terminal and run:

```
./gradlew cordovaRelease
```
This will build fresh `.aar` package and copy it to the `cordova-cordova-plugin-background-fetch` working copy in the right place.


---

Copyright (c) 2017 Transistor Software <info@transistorsoft.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
