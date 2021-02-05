============
DCML Corpora
============

What is this?
=============

This is a meta-repository containing all corpora published and curated by the `Digital and Cognitive Musicology Lab Lausanne <https://www.epfl.ch/labs/dcml/>`__. Currently, only one corpus (the Annotated Beethoven Corpus, ABC) is publicly available, but more are to follow in 2021.

What do the corpora include?
============================

At the heart of every subcorpus is a folder called ``MS3`` containing a set of annotated music scores in the `MuseScore 3 <https://musescore.org/>`__ file format ``.mscx``.

Downloading the data
====================

This repository contains submodules. You can use this command to clone it

``git clone --recurse-submodules -j8 https://github.com/DCMLab/dcml_corpora.git``

``-j8`` is available from git >= 2.8 and fetches up to 8 submodules at a time in parallel.
