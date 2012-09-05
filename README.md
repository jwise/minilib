minilib
=======

`minilib` is a compilation of chunks of code accumulated over the years,
intended for usage as a "non-standard C library".  Most of it should be
suitable for simply plopping down in a bare metal environment to add a
little bit of extra usability when no other libc is around.  It contains
some basic string/memory functions, a tiny allocator, and a tiny string
formatter; more things may come in the future.

It is arranged such that it should be easy to copy in single C files, as
incrementally needed.

History
-------

`minilib` was originally developed as part of
[NetWatch](https://github.com/jwise/netwatch), a System Management Mode
remote administration console.  It then went on to be used in
[VirtexSquared](https://github.com/teamdragonforce/virtexsquared), and
extended some further there.

Authors
-------

`minilib` is primarily maintained by Joshua Wise <joshua@joshuawise.com>. 
Also contributing:

  * Jacob Potter <jacobdp@gmail.com>: primary work on `minilib` from the
    NetWatch era; atoi
  * Elizabeth Fong-Jones <elly@leptoquark.net>: fmt; qalloc
  * Wes Filardo <nwf@cs.jhu.edu>: stdarg
