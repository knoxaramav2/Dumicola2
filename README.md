# Dumicola2
A redesign of Dumicola, starting with a focus on parallel mobile/desktop development.


## Building


## Directory Structure
Dumicola is broken up into four related sections to maximize code reuse. As Dumicola is meant to be used for desktop, mobile, and embedded applications, each of these are given their own top level source directory, containing their respective projects. Additionally, as these are developed around a common system, a fourth **common** directory is included. Here is where most of the primary buisiness logic and models are kept, and will be used between the other three projects. 

At the root level, a CMakeLists.txt file is used to build each project. See the **Building** section above for details.

Each section will contain its own README for additional development information.