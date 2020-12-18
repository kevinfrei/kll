## WARNING:
> This stuff is archived because I've moved on to manufacturing my *own* keyboards. Feel free to look around, but I don't touch this stuff at all anymore (I no longer even own an ErgoDox)

Warning: My KLL is based on my fork of the controller code. It will not work properly with an unforked controller repo, because I have a different base layer. Please keep that in mind...

kll - keyboard layout language
==============================

[![https://travis-ci.org/kiibohd/kll](https://travis-ci.org/kiibohd/kll.svg?branch=master)](https://travis-ci.org/kiibohd/kll)

[![Visit our IRC channel](https://kiwiirc.com/buttons/irc.freenode.net/input.club.png)](https://kiwiirc.com/client/irc.freenode.net/#input.club)

## If you're trying to compile keyboard firmware, you want [THIS](https://github.com/kiibohd/controller/)

KLL Compiler
------------

Most current version of the [KLL Spec](https://github.com/kiibohd/kll-spec).

Uses [funcparserlib](https://code.google.com/p/funcparserlib/)


Usage
-----

### General Usage

```bash
kll <kll files>
```

### Kiibohd Controller Usage

```bash
kll <misc kll files> --config <config/capability kll files> --base <basemap kll files) --default <default layer kll files> --partial <partial layer 1 kll files> --partial <partial layer 2 kll files>
```

See `kll --help` for the most up to date documentation


Unit Tests
----------

Unit tests can be found in the [tests](tests) directory.
They are run by Travis-CI, but can be useful when testing your own changes.

Remember to add new tests when adding new features/changes.


Patches/Features/Backends
-------------------------

Completely welcome :D
