About
-----

An implementation of a lexer for the GAP language, to be used in the Pygments highlighting system. See

* [gap-system.org](http://gap-system.org)
* [pygments.org](http://pygments.org)

This is very much a work-in-progress and at the moment.

Installation
------------

There is no automated installation available at the moment, but according to some of the projects that should be possible. As for now, you have to add the line

    'GAPLexer': ('pygments.lexers.gaplexer', 'GAP', ('gap',), ('*.gap',), ('text/x-gap',)),

to the file `_mapping.py` in the `pygments/lexers/` directory and either put the file `gaplexer.py` in that directory or create a soft link to it.