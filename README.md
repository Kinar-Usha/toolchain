# toolchain
32 bit ELF build toolchain


1. sudo ap-get update.
2. sudo apt install build-essential nasm mtools qemu-system-x86.
3. git clone "	".
4. make -j.
(edit the makefile to use more cores)

## ERROR handling
if you get this error =
configure: error: Building GCC requires GMP 4.2+, MPFR 2.4.0+ and MPC 0.8.0+.
Try the --with-gmp, --with-mpfr and/or --with-mpc options to specify
their locations. Source code for these libraries can be found at
their respective hosting sites as well as at
ftp://gcc.gnu.org/pub/gcc/infrastructure/. See also
http://gcc.gnu.org/install/prerequisites.html for additional info. If
you obtained GMP, MPFR and/or MPC from a vendor distribution package,
make sure that you have installed both the libraries and the header
files. They may be located in separate packages.


solution 
1. cd ~/.local/bin/i686....(whatever verision)/build/gcc.....(whatever version)
2. ./contrib/download_prerequisites]
