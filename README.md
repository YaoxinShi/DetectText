DetectText
==========

Detect text with stroke width transform.

## Dependencies
OpenCV 4.12
boost 1.67 (1.72 not working) https://dl.bintray.com/boostorg/release/1.67.0/binaries/boost_1_67_0-msvc-14.1-64.exe

## Compile

mkdir build
using CMake GUI, input code folder and build folder
config -> generate -> open

## Run
./TextDetection input_file output_file dark_on_light
where dark_on_light is 1 or 0, indicating whether the text is darker or lighter than the background.

## More 
Details on the algorithm can be found in:
http://www.cs.cornell.edu/courses/cs4670/2010fa/projects/final/results/group_of_arp86_sk2357/Writeup.pdf