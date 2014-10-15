================
 Title |travis|
================

.. sectnum::
.. contents::


Chapter
=======

`1 backquote` <=> ``2 backquotes``

.. code:: python

   def my_function():
       "just a test"
       print 8/2

.. code:: emacs-lisp

   (add-to-list 'company-backends 'company-ghc)


Section
-------
link: Google_

subsection
~~~~~~~~~~
image: |lazycat|

.. |lazycat| image:: lazycat.png
             :alt: Lazy Cat

Before include

.. include:: other.txt

After include

.. class:: table
.. _tables:

tables
~~~~~~

.. table:: Truth table for "not"

   =====  =====
     A    not A
   =====  =====
   False  True
   True   False
   =====  =====

.. csv-table:: Frozen Delights!
   :header: "Treat", "Quantity", "Description"
   :widths: 15, 15, 30

   "Albatross", 2.99, "On a stick!"
   "Crunchy Frog", 1.49, "If we took the bones out, it wouldn't be
   crunchy, now would it?"
   "Gannet Ripple", 1.99, "On a stick!, br |br| in |br| table"

.. _Google: https://www.google.com
.. |travis| image:: https://api.travis-ci.org/iquiw/jsonconfig-mode.svg
            :target: https://travis-ci.org/iquiw/jsonconfig-mode
.. |br| raw:: html

   <br/>
