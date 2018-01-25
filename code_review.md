---
title: "Code Review - IceCube Open Source"
author: "IceCube Collaboration"
layout: main
---

# IceCube Open Source

## Code Review

A code review covers code quality, testing, and documentation.

### Code Quality


### Testing

There *must* be at least one test or example script that can be
run to exercise the code.  The difference between a test and an example
is that the test will verify the result, while the example just checks
if it runs.

Any tests / examples must have good default arguments so they can be run
under continuous integration.  This allows us to provide support for
checking a project against new compilers, libraries, and operating systems.

### Documentation

The bare minimum of documentation is a README file explaining what the
project is, how to build it, and a way to use it.  As an example:

    The Example Project

    This project is an example to show how to write a project README file.

    It uses the standard Python build process, of `python setup.py install`.

    The package is then available in Python by importing `example`.
    An example script is provided at `resources/example.py`.


[IceCube Collaboration]: https://icecube.wisc.edu

[IceCubeOpenSource]: https://github.com/IceCubeOpenSource