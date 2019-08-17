# DNA-to-Protein-Sequence-with-Python
Here, I have written python code to convert a DNA sequence to Protein.
Here are the instructions:
Problem 1. Write a computer program (use any programming language of your choice) to convert the DNA sequence into protein sequence, i.e., determine the sequence of amino acids from the DNA sequence, using the below genetic code: 
Genetic_code= { 
'ATA':'I', 'ATC':'I', 'ATT':'I', 'ATG':'M', 'ACA':'T', 'ACC':'T', 'ACG':'T', 'ACT':'T', 'AAC':'N', 'AAT':'N', 'AAA':'K', 'AAG':'K', 'AGC':'S', 'AGT':'S', 'AGA':'R', 'AGG':'R', 'CTA':'L', 'CTC':'L', 'CTG':'L', 'CTT':'L', 'CCA':'P', 'CCC':'P', 'CCG':'P', 'CCT':'P', 'CAC':'H', 'CAT':'H', 'CAA':'Q', 'CAG':'Q', 'CGA':'R', 'CGC':'R', 'CGG':'R', 'CGT':'R', 'GTA':'V', 'GTC':'V', 'GTG':'V', 'GTT':'V', 'GCA':'A', 'GCC':'A', 'GCG':'A', 'GCT':'A', 'GAC':'D', 'GAT':'D', 'GAA':'E', 'GAG':'E', 'GGA':'G', 'GGC':'G', 'GGG':'G', 'GGT':'G', 'TCA':'S', 'TCC':'S', 'TCG':'S', 'TCT':'S', 'TTC':'F', 'TTT':'F', 'TTA':'L', 'TTG':'L', 'TAC':'Y', 'TAT':'Y', 'TAA':'_', 'TAG':'_', 'TGC':'C', 'TGT':'C', 'TGA':'_', 'TGG':'W', } 
Each student shall download a unique DNA sequence corresponding to a different chromosome (as per the instructions given on page-2 onwards and Table 1). The output of the program should be the sequence of amino acid for all the possible proteins coded by the DNA sequence and the total count of proteins. [7 Marks] 
Hint: Start reading the DNA sequence from first position until you find the triplet “ATG”, (start codon), once you find the ATG then read 3 letters at a time and convert it to corresponding amino acid (using genetic code) until you find any of the triplet “TAA” 
1 
or “TAG” or “TGA” (stop codons), once you find any of these triplets then place ‘_’ and stop. Again start searching for “ATG” triplet from the next position and do the same process till the end of the DNA sequence. 
Example: Sample DNA sequence 
GGATCGATGCCCCTTAAAGAGTTTACATATTGCTGGAGGCGTTAACCCCGGACCGGGTTTATG---------- 
Start Protein-1 Stop Start Protein-2 
Problem 2. The output of the above program will be the sequence of amino acid corresponding to each segment of start----------------------------------------stop positions of the DNA sequence of the chromosome. Thus you have the list of possible proteins that can be coded by the DNA sequence. State the length of longest and shortest protein and its amino acid composition in terms of polar and non-polar amino acids. [3 Marks] 
CSC: S. No. 1-31: Chr1-Chr31 from the below URL [i.e., S. No. 1 will take Chr-1, S.No. 2 Chr-2....... and so on...] 
Horse: 
ftp://ftp.ncbi.nih.gov/genomes/Equus_caballus/ 
CSC: S. No. 32-60: Chr1-Chr29 from the below URL 
Cow: 
ftp://ftp.ncbi.nih.gov/genomes/Bos_taurus/ 
Download the file with "fa.gz" extension and extract it, which is the input DNA sequence for the program 

