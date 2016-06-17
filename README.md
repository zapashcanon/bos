Bos — Basic OS interaction for OCaml
-------------------------------------------------------------------------------
%%VERSION%%

Bos provides support for basic and robust interaction with the
operating system in OCaml. It has functions to access the process
environment, parse command line arguments, interact with the file
system and run command line programs.

Bos works equally well on POSIX and Windows operating systems.

Bos depends on [Rresult][rresult], [Astring][astring], [Fmt][fmt],
[Fpath][fpath] and [Logs][logs] and the OCaml Unix library. It is
distributed under the ISC license.

[rresult]: http://erratique.ch/software/rresult
[astring]: http://erratique.ch/software/astring
[fmt]: http://erratique.ch/software/fmt
[fpath]: http://erratique.ch/software/fpath
[logs]: http://erratique.ch/software/logs

Home page: http://erratique.ch/software/bos  
Contact: Daniel Bünzli `<daniel.buenzl i@erratique.ch>`

## Installation

Bos can be installed with `opam`:

    opam install bos
    
If you don't use `opam` consult the [`opam`](opam) file for build
instructions.

## Documentation

The documentation and API reference is automatically generated by from
the interfaces. It can be consulted [online][doc].

[doc]: http://erratique.ch/software/bos/doc/

