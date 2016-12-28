# Basic-Network-Measurements-using-iGraph-C-C-
1. Some basic (and ad-hoc) codes to get network quantities using iGraph/C/C++

2. iGraph is available at http://igraph.org/

3. Once you have installed iGraph/C properly, you can compile 
  - netscalar.c
  - netprintmembership.c
 
    ** network example files : simple.edge, simpleplus.edge, ring20.edge, and star20.edge

  3.1 netscalar.c
    - usage : netscalar.bin in.edge out.network
    - ex) netscalar.bin ring20.edge dummyresult.network
      
  3.2 netprintmembership.c
    - usage : netprintmembership.bin in.edge out.network
    - ex) netprintmembership.bin simpleplus.edge dummyresult.network
    
    ** These are simple modifed suites from igraph example files. Most jobs are likely done by shell- and python-scripts utilizing these simple c-binaries.
  
    ** When the number of vertices and edges are not huge, you'd better use igraph/python in an ipython environment as an all-in-one solution.   
