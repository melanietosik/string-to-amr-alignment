String to Semantic Graph Alignment
==================================

DESCRIPTION
-----------

Code used for my undergrad thesis on String to Semantic Graph Alignment (for the PDF see [here] [1]).

Most of the code is adapted from ["Aligning English Strings with Abstract Meaning Representation Graphs" (Pourdamghani et al., 2014)] [2].

[1]: http://www.melanietosik.com/files/thesis.pdf
[2]: http://www.isi.edu/~damghani/

README
-------------

Download and install MGIZA++ from [here] [3].

[3]: http://www.kyloo.net/software/doku.php/mgiza:overview

Provide the address of mgizapp/scripts and mgizapp/bin folders in the addresses.keep file.

Provide the address of AMR and English files in the addresses.keep file, add .keep or put them in a different directory.
The data files must have one linearized AMR or one sentencee English per line.

Run script run.sh.

Output
------

AMR_Aligned.keep - Aligned English/AMR pairs.

Alignments.keep - Just the alignments.

Requirements
------------

You need g++ and MGIZA++ installed.

AUTHOR
------
Melanie Tosik, tosik@uni-potsdam.de

