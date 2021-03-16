# BMM43_Project3
Scientific Question: Is the TRPV1 sequence of humans more similar to the TRPV1 sequence of tree shrews or the TRPV1 sequence of mice?

Scientific Hypothesis: If humans actively seek spicy foods in a similar fashion to tree shrews, then the TRPV1 sequence of humans is more likely to have a higher similarity to the TRPV1 sequence of tree shrews than the TRPV1 sequence of mice.

To the run the code, you will need the following files:
  1. The R notebook (uploaded here)
  2. human_TRPV1_DNA.fasta (uploaded here)
  3. tree_shrew_TRPV1_DNA.fasta (uploaded here)
  4. mouse_TRPV1_DNA.fasta (uploaded here)

Information about where these FASTA files were found:
  To find the FASTA files containing the TRPV1 sequences for humans, tree shrews, and mice, I went to NCBI database (https://www.ncbi.nlm.nih.gov/) and selected "nucleotide" from the dropdown menu. I searched "human TRPV1", clicked on the result for accession: NM_080705.4, then clicked "send to:", then chose "file", then selected "FASTA" and downloaded the FASTA file. The same process was used to find and download the TRPV1 sequence FASTA files searching for "tree shrew TRPV1" (accession: XM_006167590.3) and "mouse TRPV1" (accession: NM_001001445.2).

The output of this code is a png file of a heatmap displaying the similarities between the TRPV1 sequences of humans, tree shrews, and mice using pairwise sequence alignment.
