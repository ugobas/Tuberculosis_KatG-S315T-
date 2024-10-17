# Tuberculosis_KatG-S315T
This repository contains data and scripts generated for the project "Fitness effect of the isoniazid resistance mutation S315T of the catalase-peroxidase enzyme katG of Mycobacterium tuberculosis"

The folder ALI contains the multiple sequence alignments (in phylips format, extension .phy) of selected sites in 146 Mycobacterium tuberculosis + Mycobacterium canetii sequences for phylogenetic analysis with RAxML-NG (Kozlov et al. 2019) and the corresponding .txt files that describe the type of mutation.

The folder TREES contains (all files are plain text files):
- the phylogenetic trees inferred with RAxML-NG for different data types and models (extension .bestTree, example AA_nosyn_STMTREV_FG.bestTree)
- The phylogenetic trees in Newick format reporting at each node name the inferred type of the KatG(315) amino acid (_S or _T), the inferred number of resistance mutations (_res), the inferred number of amino acid mutations from the root and the inferred number of secondary mutations (_sec). The branch lengths are 
- The inferred mutations at all branches, for several type of sites, inferred with with RAxML-NG and with branch lengths inferred with the model specified after .br. (extension .ancestral, example AA_nosyn_STMTREV_FG.ancestral).
- The description of the mutations inferred at all internal nodes of the tree (gene, amino acid or nucleotide change) (extension: .mutation Example: AA_nosyn_STMTREV_FG_STMTREV_AA.mutations)
- The differences between pairs of phylogenetic trees computed with the program K2_Dist (file names: Diff. Example: Diff.aa_all_JTT.aa_all_STMTREV).
- Summary of the differences between pairs of phylogenetic trees (Results_Diff.txt)
- MSA used for inferrring branch lengths and internal sequences (extension .phy, Example: mut.aa.nosyn.txt) and description of all their sites (extension. txt, Example: mut.aa.nosyn.txt)
- The inferred reproductive rates of the sequences where the S315T mutation first appeared and grouped for the internal nodes with and without the secondary mutation IG_Rv3845_C_sodA_N, for each of the 6 representative trees (Example: Results_Repr_rates_1.dat)
- The inferred substitution rates for several types of mutations and each of the 6 representative trees (Example: Results_Subst_rates_1.dat)

The folder SCORE contains the results of the ranking of the ML trees with the REGMLAME score and the indicated model (Example:  Regmlame_AA_DNA_AA_JTT_F_DNA_GTR.txt)

