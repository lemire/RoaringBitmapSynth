RoaringBitmapSynth
==================

Code for synth.  experiments on roaring bitmaps as prepared 
for the paper:

Samy Chambi, Daniel Lemire, Owen Kaser, Robert Godin,
Better bitmap performance with Roaring bitmaps,
http://arxiv.org/abs/1402.6407

Usage 
-------

* install java
* install maven 2
* type maven package
* cd target
* java -cp RoaringBitmapSynth-0.0.1-SNAPSHOT.jar:lib/* org.roaringbitmap.experiments.colantonio.Benchmark
* java -cp RoaringBitmapSynth-0.0.1-SNAPSHOT.jar:lib/* -javaagent:lib/SizeOf.jar org.roaringbitmap.experiments.colantonio.buffer.MemoryUsage
