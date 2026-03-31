# In-House-cgMLST

**cgMLST** (core genome multilocus sequence typing) is a high-resolution bacterial typing method that uses a large set of "core" genes—genes present in nearly all strains of a specific species—to identify and compare different bacterial isolates. It is an evolution of traditional MLST, which typically only analyzes 7 housekeeping genes. By looking at hundreds or thousands of genes instead, cgMLST provides much higher discriminatory power, making it essential for tracking disease outbreaks and studying bacterial evolution.

**Key Features of cgMLST**

- High Resolution: It can distinguish between very closely related strains that might appear identical using traditional 7-gene MLST.
- Standardized Nomenclature: Because it uses a fixed set of target genes, laboratories worldwide can compare results using a universal naming system.
- Core vs. Accessory Genome: A "core genome" is defined as loci present in >95% of the species' strains. Genes not in the core are considered part of the "accessory genome".
- Allele-Based: Like traditional MLST, it identifies variation by assigning unique numbers to different versions (alleles) of each gene.

**Common Applications**
- Outbreak Investigations: Identifying whether patients in a hospital are infected with the exact same bacterial strain or different ones.
- Surveillance: Monitoring the global spread of antibiotic-resistant "high-risk" clones.
- Phylogenetic Analysis: Understanding how different lineages of a species are related over time.


**Available Tools and Resources** 

- Databases: Major repositories include BIGSdb-Lm (https://bigsdb.pasteur.fr/listeria/),PubMLST (the same as BIGSdb-Lm), EnteroBase（https://enterobase.warwick.ac.uk/), and the cgMLST.org Nomenclature Server.
- Software: Popular analysis tools include Ridom SeqSphere+ and the open-source chewBBACA.
- Emerging Methods: Hash-based cgMLST is a newer approach that uses compressed digital "hashes" to represent gene sequences, allowing labs to share data quickly without needing a centralized server to assign new allele numbers
