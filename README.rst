brotli-file
===========

Add `brotli_file.open` as a file interface.
This package works with `brotli` package, but not with `brotlipy`.

.. code:: python

    import brotli_file

    f = brotli_file.open('test.br')
    print(f.readline())  # any other method will work except for seek
