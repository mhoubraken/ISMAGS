ISMAGS
======

This page contains a implementation of the Index-Based Subgraph Matching Algorithm with General Symmetries.

Queries can be specified in the following format:

	java -jar ISMAGS.jar -folder C:\myFolder\ -linkfiles "X u X X Xu_yeast.txt" -motif XZ00ZY -output outputname

The options to the ISMAGS jar are as follows:

* `-folder` specifies the location of all necessary files.
* `-linkfiles` specifies the network under study. In this example, the network contains X-type links (first `X` argument) that are undirected (`u` argument) and go from a node in an X-network to another node in an X-network (`X X` argument). The file contains the edges is named `Xu_yeast.txt`.
* `-motif` specifies the subgraph that we wish to find in the network.
* `-output` specifies the name of the file to which all motif instances will be exported.