# YoctoHelloWorld
this repo is having hello world example recipe for yocto project

1. this repo is to include the hello world in big font using start '#' .
2. this recepi will install the hello world program in root fs yocto builds "core-image-minimal".
3. if we need to include this in other image we need to add below line in respective image's .bb file.
    IMAGE_INSTALL:append += " hello"
