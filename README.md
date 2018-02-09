# Chao
# Language: R
# Input: CSV (network)
# Output: CSV (distances)
# Tested with: PluMA 1.0, R 3.2.5

PluMA plugin that computes dissimilarity using Chao's Method (Chao, 2005), which accounts for presence and absence.
The input CSV file can thus be non-normalized abundances; the expected format is rows representing samples and columns
representing community data members.
The plugin produces an output file with rows and columns representing samples, and entry (i, j) the dissimilarity 
between sample i and sample j.
