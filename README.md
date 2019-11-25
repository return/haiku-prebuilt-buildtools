# Prebuilt Haiku toolchain for Cross-compilation

Unofficial prebuilt buildtools for Haiku for various platforms. Used for cross-compiling Haiku apps and other ports requiring a cross-compiler without rebuilding the toolchain. This is currently for r1beta1 and stable releases of Haiku.

See the [releases](https://github.com/return/haiku-prebuilt-buildtools/releases) section for downloading a stable version of the cross-compiler and then proceed to the installation below.

## Installation:
1. Extract the tar.gz into the root of the generated folder or the location of the cross-compiler inside the `haiku` source folder.
2. Run `../configure --build-cross-tools x86_64 ../../buildtools` to configure the prebuilt cross-compiler.
3. It should return `Configured successfully!`


You should now be able to use the prebuilt cross-compiler in your CI of choice without rebuilding the cross-compiler from scratch.
