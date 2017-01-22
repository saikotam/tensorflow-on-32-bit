# Tensorflow on 32-bit Architecture

Tensorflow binaries are only available for 64 bit computers and 32 bit guys are left with only option to either upgrade their cpu or build it from source. (NOTE: Binaries named _x86_x64 are not 32 bit)

Building from source for 32 bit systems uses up LOTS OF RESOURCES and use external softwares which ,again, donot provide binaries for 32bit procesors!(these old PCs have to bear the brunt!).

This wil be a repository of Tensorflow binaries for 32bit processors.

The first release also has the Bazel 4.0 Binary(which again is built from source! Because 32 bit binaries are not being released by Bazel Team as well!)

The build logs are attached along with the releases which include almost all the errors posible to commit by a "Newbie" with an Old PC!

# Using the Binaries:
Tensorflow .whl can be installed via pip

 "This binary is self-contained, so it can be copied to a directory on the PATH (e.g., /usr/local/bin) or used in-place."
