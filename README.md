# IO Streams Benchmarks

This project attempts to quantify the performance of [io][], the IO stream
library for D, in comparison with [std.stdio][], the C standard library (i.e.,
[`stdio.h`][stdio.h]), and the C++ standard library (i.e.,
[`fstream`][fstream]).

[io]: https://github.com/jasonwhite/io
[std.stdio]: http://dlang.org/phobos/std_stdio.html
[stdio.h]: http://www.cplusplus.com/reference/cstdio/
[fstream]: http://www.cplusplus.com/reference/fstream/

# Getting It

```bash
git clone --recursive https://github.com/jasonwhite/io-benchmark.git
```

# Running It

Just run:
```bash
dub
```

Or, with optimizations turned on:
```bash
dub --build=release
```

Add the option `--compiler={dmd,ldc,gdc}` to switch between using one of the
three main compilers (DMD, LDC, or GDC). For example, to compile with
optimizations using LDC:
```bash
dub --build=release --compiler=ldc
```

*Note*: Compiling with GDC is currently broken.

# Results

*Coming soon to a README near you!*
