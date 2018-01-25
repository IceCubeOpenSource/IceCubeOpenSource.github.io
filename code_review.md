---
title: "Code Review - IceCube Open Source"
author: "IceCube Collaboration"
layout: main
---

# IceCube Open Source

## Code Review

A code review covers code quality, testing, and documentation.

We can help find someone to perform the review, but it us up to you
to fix any issues noted.

### Code Quality

We are looking for general things here, like comments to explain difficult
code or variables that have more descriptive names than `a`,`b`,`c`.

This is meant to be a light pass, so no need to adhere to [PEP8] or any
other style guide.  Just be consistent within the project.

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
project is, how to build it, and a way to use it.

As an example:

    The Example Project

    This project is an example to show how to write a project README file.

    It uses the standard Python build process, of `python setup.py install`.

    The package is then available in Python by importing `example`.
    An example script is provided at `resources/example.py`.


[PEP8]: https://www.python.org/dev/peps/pep-0008/

[IceCube Collaboration]: https://icecube.wisc.edu

[IceCubeOpenSource]: https://github.com/IceCubeOpenSource