Project currently consists of:

1. Cross compilation patches for Python 2.7.3 and 3.3.0, targeting MinGW/Darwin/Linux and MinGW builds generated from these.

2. Android toolchains for Windows, Mac OS X and Linux for Necessitas (Qt & QtCreator IDE for Android), with newer Python-capable GDB.

3. A toolchain for Linux and Windows targeting Darwin (based on work by iPhoneDev, OpenDarwin, javacom, saurik and xchain but heavily patched).

4. A build of the nano text editor for Windows.

5. Random other things used for Necessitas (e.g. 7za for Mac OS X).

The source code for these can be found here, at http://gitorious.org/~mingwandroid, http://github.com/mingwandroid and also as part of the Necessitas Project / Qt Project.

Most of the work here is released under the GPL, some bits under the APSL and some under the UoI/NCSA Open Source License.

Note: I don't work on these projects under the banner of mingw-and-ndk at code.google.com anymore. The Windows parts have been subsumed into MSYS2, the Python-capable Android NDK GDBs have been upstreamed into the official Google Android NDK and continued development on the Darwin-targetting cross compilers happens at https://github.com/diorcety/crosstool-ng.