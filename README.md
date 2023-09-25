# NARBL
A script for CRISPR detection in (meta)genomic data using repeat linkage

## Inputs: 
a FASTA file of (meta)genomic reads containing your repeat of interest (readfile_in); a FASTA file with repeat sequence to search for (repfile_in)

The name of readfile_in should be `repeatid`.reads, where `repeatid` is the fasta identifier of the repeat of interest

## Requires: 
fuzznuc, blast+, fastx toolkit

## Usage: 
narbl.sh readfile_in repfile_in
