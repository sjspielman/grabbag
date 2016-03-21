# grabbag
Various scripts I have written that seem useful


### `align_pal2nal.py`
This script is a Python version of the common "pal2nal" pipeline (Protein ALignment To Nucleotide ALignment). It back-translates a file of coding sequences to amino-acid data, aligns the amino-acid data, and returns both protein and nucleotide alignments.
The script uses MAFFT to align sequences, although you can certainly add your favorite aligner into the mix.
Requires the Biopython library, as well as [mafft](http://mafft.cbrc.jp/alignment/software/), whose executable should be available in the path.

Usage: `python align_pal2nal.py <infile>`. Enter `python align_pal2nal.py -h` for more options.