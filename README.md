gradle-lesscss-sample
=====================
A sample Gradle build using [Gradle LESSCSS plugin](https://github.com/msgilligan/gradle-lesscss-plugin)

Getting started
---------------

1. Clone this repo
1. Clone [gradle-lesscss-plugin](https://github.com/msgilligan/gradle-lesscss-plugin) 
1. Build and install to your local Maven repo:
        cd PATH-TO/gradle-lesscss-plugin
        gradle install
1. Build the Sample:
        cd PATH-TO/gradle-lesscss-sample
        gradle less
    
The compiled output of build.less should be in `build/less/basic.less.css`.  You should also see the downloaded less Javascript in `build/downloads/less-rhino-1.1.3.js`.

License
-------
Licensed under the terms of the Apache Software License 2.0

Acknowledgment(s)
-----------------
This sample is based upon source code e-mailed to me (with Apache 2 license in the headers) by [Luke Daley](https://github.com/alkemist) on March 3, 2012.
