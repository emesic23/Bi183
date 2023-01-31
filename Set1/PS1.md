# Problem 1
## a. What is the role of the UMI?
The role of the UMI is that they are Barcodes used to distinguish molecules.
They are one step of generating a library.
They allow us to identify and remove duplicates.

## b. What is the library produced?
The library produced by these methods is a collection of cDNA molecules generated from the RNA of individual cells. It contains information about the number and sequence of all the genes expressed in a cell. 

## c. Which droplet-based method demonstrates sub-poisson loading of cells? What does sub-poisson mean and how is it achieved?
The 10x genomics method and the inDrops method both demonstrate sub-poisson loading of cells. 

Poisson is a distribution that models rare random events. In the case of droplet methods, it models the rate of errors that occur in droplets such as doublets, no capture, collision, and split errors. sub-poisson means that these errors occur in these methods less frequently than expected from a poisson model. They achieve this by using man-made "squishy" beads that can be tuned to get inside drops at a constant rate. 

## d. What does 3' capture refer to?
3' end of an RNA molecule has a poly-A tail. 3' capture refers to methods that sequence the 3' end of transcripts. Methods that are 3' capture have primers that look for the poly-A tail and do transcription there. The 3' end is more highly expressed than the 5' end usually. 

## e. For 3' 10X sequencing, write the order of events for generating the final, sequenced library.
1. Cell capture and lysis
2. 3' transcript capture and barcoding
3. Reverse Transcription and amplification
4. cDNA fragmentation and size selection
5. Addition of sample index/label (sample index PCR) 
6. single- or paired-end sequencing

# [Problem2 Link](https://colab.research.google.com/drive/10u5KnaFkh9f4ltAsEljeLNFqJuW0EZBn?usp=sharing)

# [Problem3 Link](https://colab.research.google.com/drive/1OQi7dxRFzZXoc7OzNYFnXSWSrVKHRKOw?usp=sharing)