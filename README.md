treap
=====

This Go package provides a balanced binary search tree data structure, expected to have
logarithmic height.

For more on treaps, check out the following links:

* [wikipedia](http://en.wikipedia.org/wiki/Treap)
* [Treaps: The Magical Awesome BBT](http://pavpanchekha.com/programming/treap.html)

This implementation borrows a lot of ideas from [GoLLRB](https://github.com/petar/GoLLRB).

Installation
------------

Use `goinstall`:

    goinstall github.com/stathat/treap

That's it.

If you are building your code with `goinstall`, you can skip the previous step and just
import `treap` as follows:

    import (
            "github.com/stathat/treap"
    )

Usage
-----

Examples available at [www.stathat.com/src/treap](http://www.stathat.com/src/treap).

Status
------

This package was extracted from production code powering [StatHat](http://www.stathat.com),
so clearly we feel that it is production-ready, but it should still be considered
experimental as other uses of it could reveal issues we aren't experiencing.

Contact us
----------

We'd love to hear from you if you are using this in your projects!  Please drop us a
line: [@stat_hat](http://twitter.com/stat_hat) or [contact us here](http://www.stathat.com/docs/contact).

About
-----

Written by Patrick Crosby at [StatHat](http://www.stathat.com).  Twitter:  [@stat_hat](http://twitter.com/stat_hat)
