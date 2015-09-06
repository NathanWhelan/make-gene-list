# make-gene-list
This script will output a file called "partFinderGeneList.txt" which will be a list of single gene partitions. It was designed to be used for PartitionFinder, but it also useful for other programs such as BaCoCa or creating a gene block for a large supermatrix. Gene list formats for programs other than PartitionFinder may be slightly different. Most differences can easily be made with simple sed commands.

To create a list of partitions, run this script in a directory with single gene alignments in fasta format. As written, fasta files should have the extension ".fas", but this can be easily modified within the script for your purposes.
