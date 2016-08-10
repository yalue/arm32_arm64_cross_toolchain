ARM64 (aarch64) Cross Toolchain for ARM (aarch32) Hosts
=======================================================

About
-----

This is a cross toolchain containing pre-built binutils and gcc. The tools run
on a 32-bit ARM host and target ARM64. Currently, this provides version 4.9.4
of gcc and version 2.27 of GNU binutils.

These tools were originally compiled in order to build kernel modules for the
Jetson TX1. See
[this wiki page](https://github.com/yalue/PeriodicTaskReleaser/wiki/Building-Kernel-Modules-on-the-TX1)
for instructions on how to compile the kernel modules. Using this repository
will allow you to skip the steps pertaining to building a cross compiler.

Usage
-----

Clone this repository, and add the `bin/` subdirectory to your PATH.
