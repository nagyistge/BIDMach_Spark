# BIDMach_Spark
Code to allow running BIDMach on Spark including HDFS integration and lightweight sparse model updates (Kylix). 

.h2 Dependencies

This repo depends on BIDMat, and also on lz4 and hadoop. Assuming you've built a working BIDMat jar, copy these files into the lib directory of this repo. i.e.

<pre>cp BIDMat/BIDMat.jar BIDMach_Spark/lib
cp BIDMat/lz4-*.*.jar BIDMach_Spark/lib</pre>

and from
