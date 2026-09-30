# Characterization of the Plastid Genome of *Oryza sativa*

## Student Information

**Name:** Eugene Kim Ansag  
**Course/Section:** Cell and Molecular Biology - A


## Chosen Genus and Species

- **Genus:** *Oryza*
- **Species:** *Oryza sativa* (Japonica Group)


## NCBI Accession and Source Links

- **NCBI RefSeq Accession:** NC_001320.1
- **NCBI Nucleotide Record:** https://www.ncbi.nlm.nih.gov/nuccore/NC_001320.1
- **NCBI GenBank Record:** https://www.ncbi.nlm.nih.gov/nuccore/NC_001320.1?report=genbank


## Date Retrieved

**Date Retrieved:** September 29, 2026


## Genome Size and Plastome Summary

The chloroplast genome of *Oryza sativa* (Japonica Group) is a complete circular plastome with a total genome size of **134,525 bp** and a **GC content of 38.99%**.

The plastome exhibits the typical quadripartite structure found in most flowering plants and consists of:

- **Large Single-Copy (LSC) region:** 80,592 bp
- **Small Single-Copy (SSC) region:** 12,335 bp
- **Inverted Repeat A (IRa):** 20,799 bp
- **Inverted Repeat B (IRb):** 20,799 bp

The plastome contains approximately **113 unique genes**, including protein-coding genes, transfer RNA genes, and ribosomal RNA genes.


## Genome Download and Galaxy Upload Procedure

The complete chloroplast genome of *Oryza sativa* (NC_001320.1) was obtained from the NCBI RefSeq database.

1. The FASTA sequence file was downloaded from the NCBI Nucleotide record using the FASTA display option.
2. The annotated genome record was obtained from the GenBank format page.
3. The FASTA file was uploaded to Galaxy (https://usegalaxy.org).
4. Galaxy automatically recognized the file as FASTA format.
5. The uploaded dataset was renamed using the species name and accession number.


## Galaxy History and Tools Used

### Galaxy History Name

`Plastid_Oryza_Ansag`

### Tools Used

- FASTA Statistics
- gfastats / Sequence Statistics

### Results

| Parameter | Value |
|------------|---------|
| Genome Length | 134,525 bp |
| Number of Sequences | 1 |
| GC Content | 38.99% |


## Gene Content and Important Observations

### Gene Content Summary

| Category | Count |
|-----------|---------|
| Total Unique Genes | ~113 |
| Protein-Coding Genes | ~80 |
| tRNA Genes | 30 |
| rRNA Genes | 4 |

### Important Observations

1. The plastome displays the typical **LSC-SSC-IR quadripartite organization** found in most angiosperm chloroplast genomes.
2. All genes located within the inverted repeat regions are duplicated, resulting in multiple copies of several genes.
3. The **rps12** gene undergoes trans-splicing, with exon 1 located in the LSC region and exons 2 and 3 located within the IR regions.
4. Several genes contain introns, including:
   - *ndhA*
   - *ndhB*
   - *petB*
   - *petD*
   - *clpP*
   - *rpl2*
   - *rpl16*
   - *atpF*

5. The plastome contains structural rearrangements characteristic of grasses (Poaceae), including plastid DNA inversions reported during cereal plastome evolution.


## Data Sources and References

### Databases

- NCBI RefSeq Nucleotide Database  
  https://www.ncbi.nlm.nih.gov/nuccore/NC_001320.1

- NCBI GenBank Record  
  https://www.ncbi.nlm.nih.gov/nuccore/NC_001320.1?report=genbank

### Primary Reference

Hiratsuka J., Shimada H., Whittier R., Ishibashi T., Sakamoto M., Mori M., Kondo C., Honji Y., Sun C.R., Meng B.Y., Li Y.Q., Kanno A., Nishizawa Y., Hirai A., Shinozaki K., and Sugiura M. (1989).
**The complete sequence of the rice (*Oryza sativa*) chloroplast genome: intermolecular recombination between distinct tRNA genes accounts for a major plastid DNA inversion during the evolution of the cereals.**
*Molecular and General Genetics*, 217(2-3), 185-194.
DOI: https://doi.org/10.1007/BF02464880 


## Reproducibility Statement

Another student can reproduce this analysis by:

1. Accessing the NCBI RefSeq record NC_001320.1.
2. Downloading the complete chloroplast genome FASTA sequence.
3. Uploading the FASTA file to Galaxy.
4. Running the FASTA Statistics or gfastats tool.
5. Recording genome size, sequence count, and GC content.
6. Reviewing the GenBank annotation to identify gene content, plastome structure, introns, duplicated genes, and other notable features.
7. Comparing the obtained results with the published annotation record.
