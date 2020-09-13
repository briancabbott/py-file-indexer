


metatarget — 
   an object that is created when the build description is parsed and can be 
   called later with specific build properties to generate actual targets.

build property - 
   A build property is a variable that affects the build process. It can be specified on the command
   line, and is passed when calling a metatarget. While all build tools have a similar mechanism, 
   Boost.Build differs by requiring that all build properties are declared in advance.


property propagation