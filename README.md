# Bioinformatics
Genome replication is one of the most crucial tasks carried out in a cell. This occurs right before cell division occurs and as a result of it, the genetic material
gets replicated so that it can be equally divided into the two daughter cells.
This project aims to mimic DNA replication algorithmically and analyze the underlying biological process
 STEP 1 : Finding the ori site (origin of replication) -> Locating ori presents an important task not only for understanding how cells replicate but also for various             biomedical problems. The initiation of replication in a bacterial cell is mediated by DnaA, a protein that binds to a short segment within the ori known as a           DnaA box. By finding the highly repetitive subunits in a particular DNA sequence provided. Experiments have revealed that bacterial DnaA boxes are usually 9           nucleotides long. Therefore, we need to find a list of all repetitive 9-mers in the sequence provided (Clump-finding)
          Another method to find ori is to analyze the genome's half strands.
          Although most bacteria have circular genomes, we will assume them to be linear, a reasonable simplifying assumption because the length of the window is much           shorter than the length of the genome. ori occurs where the reverse half-strand transitions to the forward half-strand so by finding the locations of the two           we can easily find the ori.
          Another method called the Skew method can also be used.
          Sequences similar to the DnaA boxes are also capable of binding DnaA and therefore, we can also find similar repetitive sequences in the DNA and identify               them as the ori. This can be done by fixing a maximum Hamming distance.
 STEP 2 : Finding regulatory motifs or transcription factor binding sites in the upstream region of the gene using greedy motif algorithm
 STEP 3 : Using Laplace's Rule of Succession to optimize the Greedy Motif Search algorithm
          -> Randomized motif search (Monte Carlo algorithm)- quickly finds approximate results
          -> Gibbs Sampling (more cautious than randomized method)
