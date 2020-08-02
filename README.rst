brotli-file
===========

Add `brotli_file.open` as a file interface.

.. code:: python

    import brotli_file

    f = brotli_file.open('test.br')
    print(f.readline())  # any other method will work except for seek
