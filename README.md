# ProtPepRFScorePaper2021
RF models and selected data from the protein-peptide RF scoring paper

The PDBQT files in the receptors and peptides folders are the files
provided by the authors of:

   Robert Rentzsch, Bernhard Y. Renard, Docking small peptides remains a great
   challenge: an assessment using AutoDock Vina, Briefings in Bioinformatics,
   Volume 16, Issue 6, November 2015, Pages 1045–1056,
   https://doi.org/10.1093/bib/bbv008

<h2>Content</h2>

<h3>classifiers.tgz</h3>
use tar zxvf classifiers.tgz to expand this file into the classifier folder containing the pickled RF models described in the paper:

Michel F. Sanner, Leonard Dieguez, Stefano Forli, Ewa Lis. Improving Docking Power for peptides using Random Forest, JCIM ...

<h3>contactingChains.csv</h3>
This comma separated file provides for each entry the complex name, the list of protein chains ID(s) and the number and length of these chains, the chain
ID(s) short peptidic chains (i.e. chains with less than 50 amino acids and different from the peptide ligand) their number and length

