ITI
===

ITI - Incremental Tree Inducer (unofficial mirror from http://people.cs.umass.edu/~lrn/iti/index.html)

This is a mirror of the ITI Incremental Tree Inducer, created by Paul Utgoff at UMass Amherst.  My sole intention for uploading this to github is so that it remains available to the machine learning community, as the Machine Learning Laboratory is no longer operating.

The code is copyrighted by UMass Amherst, but is available for research use.  Below I've included a copy of the original entry page for the website.

-----------------------------------------------------------------------------
Machine Learning Laboratory

Incremental Decision Tree Induction

ITI (Incremental Tree Inducer) is a program that constructs decision trees automatically from labeled examples. Although the program is called ITI, it includes both the ITI and DMTI (Direct Metric Tree Induction> algorithms. One runs the ITI program, but with certain command options invokes the DMTI algorithm within.
Decision trees: http://people.cs.umass.edu/~lrn/iti/dtree-background.html 

The most useful aspect of the ITI algorithm is that is provides a mechanism for incremental tree induction. If one has already constructed a tree, and then obtains a new labeled example, it is possible to present it the algorithm, and have the algorithm revise the tree as necessary. The alternative would be to build a new tree from scratch, based on the now augmented set of labeled examples, which is typically much more expensive. ITI handles symbolic and numeric variables, and missing data values. It includes a virtual pruning mechanism too.

ITI is implemented in ANSI C, and it has been actively maintained since 1994. Version 3.10 (23 March 2001) is current. The code distribution includes several other programs, including a tree drawing program PST that generates PostScript code. An article about ITI and DMTI appears in October 1997 Machine Learning journal.
Article: ftp://ftp.cs.umass.edu/pub/iti/iti.ps 

The source code is protected by copyright, but is available for individual research purposes. If you wish to use this code in any other way, you must sign a licensing agreement covering your intended activity. This is quite easy to do - send me email for more info.
Source code link: http://people.cs.umass.edu/~lrn/iti/license.html

The documentation now lives on these Web pages, and is therefore no longer included in the distribution. It is quite easy to install the code. There is a log of changes from each version to the next, directions for running ITI and DMTI, and similar directions for running PST.
Installation instructions: http://people.cs.umass.edu/~lrn/iti/iti-how-to-install.html
Log of changes: http://people.cs.umass.edu/~lrn/iti/iti-change-log.html
Directions for running ITI and DMTI: http://people.cs.umass.edu/~lrn/iti/iti-how-to-run.html
Directions for running PST: http://people.cs.umass.edu/~lrn/iti/pst-how-to-run.html


Last Updated: March 23, 2001 
© Copyright 2001, All Rights Reserved, Paul Utgoff, University of Massachusetts

