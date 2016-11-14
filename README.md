[](This file is part of kernel32-sys. It is subject to the license terms in the COPYRIGHT file found in the top-level directory of this distribution and at https://raw.githubusercontent.com/lemonrock/kernel32-sys/master/COPYRIGHT. No part of kernel32-sys, including this file, may be copied, modified, propagated, or distributed except according to the terms contained in the COPYRIGHT file.)
[](Copyright © 2016 The developers of kernel32-sys. See the COPYRIGHT file in the top-level directory of this distribution and at https://raw.githubusercontent.com/lemonrock/kernel32-sys/master/COPYRIGHT.)

# kernel32-sys

This crate is a shim replacement for the junkware shite that is the real kernel32-sys crate and its deeply broken dependency winapi-build written by some Windows fanboy-aegit. Why, in the name of all that is sensible, does that crate run a build script on a Linux system? This makes cross-compiling on Alpine Linux using a patchelf'd rustc that uses glibc (uggh) (because the rust core team _still_ haven't delivered a statically linked musl binary after over a year because of arcane conversations and a lack of experience with devops). And because cargo doesn't make it easy to override rustc just for build scripts. Tried to get the idea through the developer's head, have given up.


## Licensing

The license for this project is MIT.

[kernel32-sys]: https://github.com/lemonrock/kernel32-sys "kernel32-sys GitHub page"
