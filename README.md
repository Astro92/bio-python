# bio-python

This is a small package of python scripts that have aided me during my structural biology PhD.


PDB-to-FASTA.py

A python script that will take a standard format .pdb file and output a .fasta file of the protein sequence. The script assumes the protein chain of interest is 'A'.

uniprotID-to-speciesname.py

This script will convert the uniprot ID found within .fasta files, and replace it with the species name instead.
i.e.  >Q63TL0   ----->    >Burkholderia pseudomallei (strain K96243)
