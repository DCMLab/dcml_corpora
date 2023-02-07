============
DCML Corpora
============

What is this?
=============

This is a meta-repository containing all corpora published and curated by the `Digital and Cognitive Musicology Lab Lausanne <https://www.epfl.ch/labs/dcml/>`__. Currently, only three corpora are publicly available, but more are to follow.

*ABC*
    The Annotated Beethoven Corpus containing L. v. Beethoven's string quartets.

*beethoven_piano_sonatas*
    Ludwig van Beethoven - Piano Sonatas [[DOI](https://doi.org/10.5281/zenodo.7473560)][[ZIP](https://github.com/DCMLab/beethoven_piano_sonatas/archive/refs/heads/main.zip)]

*corelli*
    Arcangelo Corelli's trio sonatas opp. 1, 3 and 4.

*chopin_mazurkas*
    Frédéric Chopin - Mazurkas [[DOI](https://doi.org/10.5281/zenodo.7473566)][[ZIP](https://github.com/DCMLab/chopin_mazurkas/archive/refs/heads/main.zip)]

*debussy_suite_bergamasque*
    Claude Debussy - Suite Bergamasque [[DOI](https://doi.org/10.5281/zenodo.7473568)][[ZIP](https://github.com/DCMLab/debussy_suite_bergamasque/archive/refs/heads/main.zip)]

*dvorak_silhouettes*
    Antonín Dvořák - Silhouettes [[DOI](https://doi.org/10.5281/zenodo.7473576)][[ZIP](https://github.com/DCMLab/dvorak_silhouettes/archive/refs/heads/main.zip)]

*grieg_lyrical_pieces*
    Edvard Grieg - Lyric Pieces [[DOI](https://doi.org/10.5281/zenodo.7473578)][[ZIP](https://github.com/DCMLab/grieg_lyrical_pieces/archive/refs/heads/main.zip)]

*liszt_pelerinage*
    Franz Liszt - Années de Pèlerinage [[DOI](https://doi.org/10.5281/zenodo.7473580)][[ZIP](https://github.com/DCMLab/liszt_pelerinage/archive/refs/heads/main.zip)]

*medtner_tales*
    Nikolai Medtner - Tales [[DOI](https://doi.org/10.5281/zenodo.7473528)][[ZIP](https://github.com/DCMLab/medtner_tales/archive/refs/heads/main.zip)]

*mozart_piano_sonatas*
    All piano sonatas by W.A. Mozart.

*schumann_kinderszenen*
    Robert Schumann - Kinderszenen [[DOI](https://doi.org/10.5281/zenodo.7473582)][[ZIP](https://github.com/DCMLab/schumann_kinderszenen/archive/refs/heads/main.zip)]

*tchaikovsky_seasons*
    Pyotr Tchaikovsky - The Seasons [[DOI](https://doi.org/10.5281/zenodo.7473586)][[ZIP](https://github.com/DCMLab/tchaikovsky_seasons/archive/refs/heads/main.zip)]








What do the corpora include?
============================

At the heart of every subcorpus is a folder called ``MS3`` containing a set of annotated music scores in the MuseScore file format ``.mscx``. In order to display the files you need to `download the data <#downloading-the-data>`_ to your computer and open them with `MuseScore 3 <https://musescore.org/download>`__. For example, the beginning of the file ``ABC/MS3/n08op59-2_01.mscx`` looks like this:

.. figure:: img/ABC_n08op59-2_01.png
    :alt: Beginning of Beethoven's 8th String Quartet op. 59/2
    :figclass: align-center

    *Beginning of Beethoven's 8th String Quartet op. 59/2 with harmony labels*

In addition to the annotated scores in the ``MS3`` folder, the following folders contain the same information in a tabular format:

* **notes**: TSV files representing one note per row
* **measures**: TSV files representing one measure per row
* **harmonies**: TSV files representing one harmony label per row

The `TSV files <https://en.wikipedia.org/wiki/Tab-separated_values>`__ (tab-separated values) can be opened with any modern data processor, programming language, or spreadsheet, for example with `LibreOffice Calc <https://www.libreoffice.org/discover/calc/>`__. They were created with the MuseScore parser `ms3 <https://github.com/johentsch/ms3>`__ which can be used to extract other information from MuseScore files, too, such as articulation, lyrics, or rests. Its `documentation <https://johentsch.github.io/ms3/build/html/manual.html#column-names>`__ includes information on what the columns in the above-mentioned TSV files contain.

Harmony Labels
--------------

The harmonic analysis in the above example follows the `DCML harmonic annotation standard <https://github.com/DCMLab/standards>`__. The labels were entered into the scores by professional music theorists.



Downloading the data
====================

Clone this repo
---------------

This repository contains submodules. You can use this command to clone it

``git clone --recurse-submodules -j8 https://github.com/DCMLab/dcml_corpora.git``

Downloading manually
--------------------

If you are unfamiliar with Git, you can download the corpora individually as
ZIP files. Click on the respective folder above (e.g. ``ABC @ <commit>``) and
click on (the green button) ``Code -> Download ZIP``.
