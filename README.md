# MapReduce-Distributed-Processing

This project involves the simulation of the MapReduce framework using multi-process programming on a single machine. MapReduce, introduced by Google, is a programming model for processing large datasets in parallel by splitting them into smaller chunks.

This project aims to replicate this functionality by dividing input data into multiple splits, processed in two phases: the map phase and the reduce phase. In the map phase, worker processes generate intermediate key-value pairs from data splits, while the reduce phase consolidates these pairs into a final output.

Two specific tasks are implemented: a "Letter Counter" that calculates the frequency of each alphabet letter in the input file and a "Word Finder" that identifies lines containing a user-specified word.

The program is designed to handle large text files efficiently, using fork() to create worker processes for each split. The MapReduce operations are user-defined, ensuring flexibility and customizability while adhering to prescribed interfaces and file naming conventions.