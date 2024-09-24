> [!WARNING] 
> TheAmbientLightSensor library hasn't been updated in a very long time and may no longer function on newer systems. If you are interested in 
> reviving this library, consider [becoming a maintainer for this project](https://github.com/processing/ambientlightsensor/issues/1).

This is a library by [Martin Rädlinger](https://www.formatlos.de/) for the programming environment Processing.

It is based on [Amit Singhs experiments](https://web.archive.org/web/20200103164052/https://osxbook.com/book/bonus/chapter10/light/) with the »Ambient Light Sensor« and provides an interface to the sensor which is built-in in every MacBookPro. Originally the sensor is intended for adjusting the keyboards and displays brightness depending on the ambient lighting conditions.

As Apple has changed the API for kernel calls sligthly and the old method is deprecated, this release of the library probably won't work with a prior OSX Version than 10.5 (Leopard). If this is the case you can always replace the libLmuTracker.jnilib (in the library folder) with the JNI file provided in the old library release (0.9)
