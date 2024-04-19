FCSParser
=================

This is forked from https://github.com/eyurtsev/fcsparser, obviously. Consult the README and documentation there.
This fork allows for arbitrary parameter numbering instead of assuming sequential numbering.

fcsparser is a python package for reading fcs files. 

Install
==================

Install this fork using git clone, not conda or pip.

Using
==================

    >>> import fcsparser
    >>> path = fcsparser.test_sample_path
    >>> meta, data = fcsparser.parse(path, reformat_meta=True)

A more detailed example can be found here: https://github.com/eyurtsev/fcsparser/blob/master/doc/fcsparser_example.ipynb

LICENSE
===================

The MIT License (MIT)

Copyright (c) 2013-2023 Eugene Yurtsev

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
