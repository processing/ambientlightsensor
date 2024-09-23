This is a library by [Martin Rädlinger](https://www.formatlos.de/) for the programming environment Processing.

It is based on Amit Singhs experiments with the »Ambient Light Sensor« and provides an interface to the sensor which is built-in in every MacBookPro. Originally the sensor is intended for adjusting the keyboards and displays brightness depending on the ambient lighting conditions.

As Apple has changed the API for kernel calls sligthly and the old method is deprecated, this release of the library probably won't work with a prior OSX Version than 10.5 (Leopard). If this is the case you can always replace the libLmuTracker.jnilib (in the library folder) with the JNI file provided in the old library release (0.9)
