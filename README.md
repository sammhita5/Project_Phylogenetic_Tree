1. Retrieved data from the UniProt database website - actin_raw.fasta.

2. Aligned the raw dataset using Clustal Omega website (https://www.ebi.ac.uk/jdispatcher/msa/clustalo) to produce the file - actin_aligned.fasta.

3. The aligned dataset (actin_aligned.fasta) was trimmed using the clipkit python library to produce the file - actin_aligned.fasta.clipkit.

4. The folder "trees" contains 3 output files which store the phylogenetic tree. The 3 files are: actin.treefile, iqt.contree and iqt.iqtree.

The tree is derived from the IQ-TREE website (https://www.hiv.lanl.gov/content/sequence/IQTREE/iqtree.html) wherein the trimmed dataset (actin_aligned.fasta.clipkit) is pasted and the following options were selected:

- <img width="785" height="223" alt="image" src="https://github.com/user-attachments/assets/52a95159-df60-428f-aee3-1894a2a18c3b" />

5. The folder "results" stores the actin phylogenetic tree image. This tree was visualized using iTOL. The image background was changed to white using the Python library pillow.

6. The .ipynb Jupyter Notebook file is "actin phylogenetic tree.ipynb" this is where the executable code resides.(To run locally use ipynb file)

7. The file 'actin phylogenetic tree.md' is Jupyter notebook's markdown (md) file through which the code snippets and their outputs are easily readable in GitHub.
   (To view in GitHub use the markdown file) 
