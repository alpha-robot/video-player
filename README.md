# Basic C video player

### How to compile

You must use GCC compiler, in addition to include Gstreamer library with the following ``pkg-config --cflags --libs gstreamer-1.0`` flag, this is how it proceeds: 

~~~
gcc index.c -o ${outputFile} `pkg-config --cflags --libs gstreamer-1.0`
~~~

You can always use the already compiled ones in the `com` folder.

### How to execute

~~~
./${outputFile} ${yourVideoFilePath}
~~~
Example: ``./player ./videos/hello.mp4``


### Links

> Installing [GCC compiler](https://gcc.gnu.org/install/)

> Installing [Gstreamer](https://gstreamer.freedesktop.org/documentation/installing/index.html?gi-language=c)
