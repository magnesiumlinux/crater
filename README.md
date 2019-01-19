crater
======

a build system in a shell script.  each software package is 
defined in cr8 file, a shell stub that gets sourced in and 
controls aspects of the build. autoconf-style packages often 
only need package name and version, and a url for the upstream 
mirror

cr8 file for many popular packages are included in the tree 
subdirectory

paths to important locations are currently hardcoded under the 
/build directory.

crater --help provides a list of options
 