# pyspark-fsgm
PySpark Frequent Subgraph Mining

A collaborative project that I got asked to work on. 

Basically this is a simple frequent subgraph mining example on spark in python. This would probably be faster in Java or Scala...

I have no idea where the dataset comes from, or what it describes, other than its the "Yeast" Dataset.

There is a paper that describes the process in hadoop that is being used as a sketch.

I don't need to generate all the graphs themselves... just all the in-order graph sequences as strings. nid, nid:w:nid, nid:w:nid:w:nid, ...