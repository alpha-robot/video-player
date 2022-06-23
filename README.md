# Basic C video player

### How to compile

You must use GCC compiler, in addition to include Gstreamer library with the following ``pkg-config --cflags --libs gstreamer-1.0`` flag, this is how it proceeds: 

~~~
gcc index.c -o ${outputFile} `pkg-config --cflags --libs gstreamer-1.0`
~~~


### How to execute

~~~
./${outputFile} ${yourVideoFile}
~~~
Example: ``./player hello.mp4``


### Links

> Installing [GCC compiler](https://gcc.gnu.org/install/)

> Installing [Gstreamer](https://gstreamer.freedesktop.org/documentation/installing/index.html?gi-language=c)
