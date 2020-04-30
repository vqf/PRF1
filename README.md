# PRF1
Supplementary material for the manuscript "Frequent birth-and-death events throughout perforin-1 evolution". Contains data from the manual annotation work and from the preliminary phylogenetic analyses.
# Annotation
The *Annotation* folder contains the output of the [*BATI* algorithm](http://degradome.uniovi.es/downloads.html). Each species folder includes as many folders as annotated genes and pseudogenes. Each of these subfolders will display:

* A `tbn` file with the `tblastn` hits used in the annotation process. If no genes were annotated in the project, this will be the only file.
* A `seq` file with the annotated coding sequence, one exon per line.
* An `aa` file with the protein translation of the `seq` sequence.
* A `gff` and an `xml` file with the coordinates of the annotation.
* A `_contig.seq` file with the genomic sequence containing the annotated gene.
* A `warnings.txt` file with custom warnings about the annotation.
* A `map.html` file with a map of the `_contig.seq` sequence.

Some folders also contain `pdf` files showing alignments of the project sequences with the human PRF1 protein as reference.

# Phylogenetics
There are three folders with the analyses of mammalian PRF1 sequences (`mammals`), fish PRF1 sequences (`flfish`) and fish c2PRF1 sequences (`C2`). Each of those folders contain the input and output files of `MrBayes`, plus a subfolder with the input and output of `protpars`.
