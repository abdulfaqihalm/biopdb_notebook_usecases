In this notebook we would like to use some Bio.PDB library to use Biopython for several use cases in structural analyses.

For the 1st to 4th problems we will use 2PTC protein which you can acces on https://www.rcsb.org/structure/2PTC. From the page, we can see that the protein has two main entities: Chain E (Trypsin) and Chain I (Trypsin Inhibitor). Latly, we will explore Superposition. 

Superposition is one of the problem when dealing with protein structure data. With superposition, we can determine whether a particular protein relates to another protein hence it can give you the functionality of the protein due to structure information is more conserve in evolution processes. For this problem we will use two methods: RMSD and Theseus-PP[1]



[1] L. S. Moreta et al., "A Probabilistic Programming Approach to Protein Structure Superposition," 2019 IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB), 2019, pp. 1-5, doi: 10.1109/CIBCB.2019.8791469. Github Repo: https://github.com/LysSanzMoreta/Theseus-PP