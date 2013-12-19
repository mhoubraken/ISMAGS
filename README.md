ISMAGS
======

This page contains a implementation of the Index-Based Subgraph Matching Algorithm with General Symmetries.

Queries can be specified in the following format:

	java -jar ISMAGS.jar -folder C:\myFolder\ -linkfiles "P u P P Pu.txt" -motif PPP -output outputname

The options to the ISMAGS jar are as follows:

* `-folder` specifies the location of all necessary files.
* `-linkfiles` specifies the network under study. In this example, the network contains P-type links (first `P` argument) that are undirected (`u` argument) and go from a node in a P-network to another node in a P-network (`P P` argument). The file contains the edges is named `Pu.txt`.
* `-motif` specifies the subgraph that we wish to find in the network.
* `-output` specifies the name of the file to which all motif instances will be exported.