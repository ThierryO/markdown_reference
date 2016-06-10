Tris and tricks for using RMarkdown
================

Chunks
======

Keep chunks compact
-------------------

You will split the code into chunks because otherwise you can't put text in between them. Still some chunks can contain a lot of code. Things get more readable when you split a long chunk into several smaller chunks by grouping code with similar functionality. E.g. one chunk to read the data, one chunk to preprocess the data and one chunk to plot the data.

Give chunks names
-----------------

An unnamed chunk starts with ```` ```{r} ````. A named chunk starts with ```` ```{r name-of-the-chunk} ````. The name of the chunks are displayed when compiling the document. Unnamed chunks are displayed as "unnamed-chunk-1". When the compilation is stopped due to an error, you will see the name of the last executed chunk. When it is named, you can find it easily in the document.

Chunk names are also used in filename for figures. Thus figure files are easy to matcht with named chunks.

Figures
=======

Created within the document
---------------------------

Externally created
------------------

Tables
======
