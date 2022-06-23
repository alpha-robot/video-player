# Basic C video player

### How to compile

You must use GCC compiler, in addition to include Gstreamer library with the following ``pkg-config --cflags --libs gstreamer-1.0`` flag, this is how it proceeds: 

~~~
gcc ${file} -o ${outputFile} `pkg-config --cflags --libs gstreamer-1.0`
~~~
Example: ``gcc index.c -o index `pkg-config --cflags --libs gstreamer-1.0` ``


### How to execute

~~~
./${outputFile} ${yourVideoFile}
~~~
Example: ``./player hello.mp4``
