
The following graphs show that, for 4 <= t <= 20, there exists a graph (the file TW_t_***.g1) with treewidth t,
such that if the length 2 ladder in that graph is extended to length 3, yielding the graph in the file TW_t_***.g2 (which has
2 more vertices and three more edges than the .g1 graph), the treewidth of the new graph is (t+1).

The TW_t_***.log file is simply the concatenation of the .g1 and .g2 files.

The graphs are in the format used by the PACE tournaments: https://pacechallenge.org/

The treewidths have been checked using the tw-exact solver by Tamaki, that was used in PACE 2016, and which is available here:
https://github.com/TCS-Meiji/treewidth-exact

The treewidth_checked.txt file shows the result of checking the graph with tw-exact. Each block of text in this file
has the form

==========================
name of the .g1 file
first line of the .g1 file
treewidth computed by tw-exact
name of the .g2 file
first line of the .g2 file
treewidth computed by tw-exact

Cheers,

Steven Kelk
9th February 2023


