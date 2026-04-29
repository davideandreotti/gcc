## GCC with Delegated Credentials support

This repository is a modified GCC source tree used to build a custom `gccgo`/`libgo` toolchain for experimental work.

### Patch scope

This fork includes local changes under:

- `libgo/go/crypto/tls`
- `libgo/go/crypto/x509`

The patchset primarily adds delegated credentials support together with related TLS/X.509 changes required by the modified `libgo` runtime.

This is not an official GCC distribution.

### Build notes for this fork

This repository should be built using GCC's standard out-of-tree build process. A typical workflow is:

```bash
mkdir -p ../gcc-rebuild
cd ../gcc-rebuild
../gcc/configure [your GCC configure options]
make -j$(nproc)
```
If desired, install with: 
```bash
make install
```
For authoritative build and installation details see:
- gcc/doc/install.texi
- http://gcc.gnu.org/install/

> **Note**: the `INSTALL` directory is deprecated. For releases, installation documentation is generated from `gcc/doc/install.texi` and copied there.

---
---

This directory contains the GNU Compiler Collection (GCC).

The GNU Compiler Collection is free software.  See the files whose
names start with COPYING for copying permission.  The manuals, and
some of the runtime libraries, are under different terms; see the
individual source files for details.

The directory INSTALL contains copies of the installation information
as HTML and plain text.  The source of this information is
gcc/doc/install.texi.  The installation information includes details
of what is included in the GCC sources and what files GCC installs.

See the file gcc/doc/gcc.texi (together with other files that it
includes) for usage and porting information.  An online readable
version of the manual is in the files gcc/doc/gcc.info*.

See http://gcc.gnu.org/bugs/ for how to report bugs usefully.

Copyright years on GCC source files may be listed using range
notation, e.g., 1987-2012, indicating that every year in the range,
inclusive, is a copyrightable year that could otherwise be listed
individually.
