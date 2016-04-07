# scan_tcga_mRNAs
Code for scanning TCGA data for the expression levels of specific genes

Authors: Peter Stockwell & Aniruddha Chatterjee

The distribution, including documentation and test data is all
contained in the tar archive tcga_mRNAs.tar.gz.

Unpack with a command like:

gzip -dc tcga_mRNAs.tar.gz | tar -xvf -

(or an equivalent) which will create a directory tcga_mRNAs containing
the package.

Note that the test_data is substantially cut down from the original
TCGA repository files in order to keep this distribution as compact as
possible.  The files included here give identical results to runs on
the original full size files.
