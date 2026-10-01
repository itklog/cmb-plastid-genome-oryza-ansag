# Lab Title: Visualize Plastid Genome Structure

**Student name:** Eugene Kim Ansag  


## Genome Specifications

* **Scientific Name:** *Oryza sativa* Japonica Group (Asian Rice)
* **NCBI Accession Number:** NC_001320.1
* **Plastid Genome Length:** 134,525 bp
* **Source of Genome File:** NCBI Nucleotide Database (GenBank Format / FASTA)
* **Visualization Software:** OrganellarGenomeDRAW (OGDRAW v1.3.1)

## OGDRAW Configuration settings

To generate the circular genome map for *Oryza sativa*, I completed the following workflow using OrganellarGenomeDRAW (OGDRAW):

1. **Accessed OGDRAW:** I navigated to the official OGDRAW web tool portal.
2. **Selected Map Mode:** I selected the standard map mode option.
3. **Uploaded Input File:** I uploaded the annotated GenBank file (`NC_001320.1.gb`) containing the sequence and feature coordinates.
4. **Configured Map Geometry:** I selected **Circular** as the genome map type.
5. **Set Sequence Source:** I designated **Plastid** as the sequence source.
6. **Detected Inverted Repeats:** I enabled the **automatic detection** option to allow OGDRAW to identify the inverted repeat boundaries ($\text{IR}_a$ and $\text{IR}_b$).
7. **Plotted GC Content:** I selected the option to draw the **GC content graph** on the inner track.
8. **Indicated Transcription Direction:** I enabled the option to display the **direction of transcription** for all gene features.
9. **Included Map Legend:** I selected the option to display the **full color-coded legend** for gene functional classifications.
10. **Annotated Introns:** I selected the option to label intron-containing genes with an asterisk (`*`).
11. **Selected Output Format:** I selected **PNG** as the primary image output format for displaying in my GitHub README, along with downloading a high-resolution SVG copy.
12. **Executed Processing:** I submitted the map generation job and waited for OGDRAW to process the annotations.


## Plastid Genome Map

![Plastid genome map](figures/Oryza_sativa_plastid_map.png)

*Figure 1: Circular genome map of the Oryza sativa Japonica Group chloroplast genome (134,525 bp) generated using OGDRAW.*


## Structural Characterization & Observations

The *Oryza sativa* plastid genome displays a classic quadripartite circular structure spanning 134,525 base pairs. It is divided into a Large Single-Copy (LSC) region, a Small Single-Copy (SSC) region, and two identical Inverted Repeat regions ($\text{IR}_a$ and $\text{IR}_b$) that physically separate the LSC and SSC. The LSC region harbors the dense majority of genes involved in photosynthesis (*psb*, *psa* complexes, *rbcL*) and gene expression (*rpo* subunit genes, ribosomal protein clusters). The SSC region is primarily characterized by the *ndh* gene family encoding components of the NADH dehydrogenase complex. The duplicate $\text{IR}_a$ and $\text{IR}_b$ regions contain identical copies of the ribosomal RNA operon (*rrn4.5*, *rrn5*, *rrn16*, *rrn23*) alongside duplicate ribosomal protein genes (*rpl2*, *rpl23*, *rps7*, *rps12*) and select tRNAs. The inner GC content graph indicates elevated GC levels within the IR regions, driven largely by the high GC density of the ribosomal RNA genes.


## Lab Answers

* **Lab Answers File:** Lab_plastid_genome_answers.md
