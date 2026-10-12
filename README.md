# Impact of Non-Synonymous SNPs on Protein Function in Breast Cancer

Whole-genome sequencing (WGS) analysis of human breast cancer data, completed during a Research Internship in Cancer Genomics at **Genomac Institute Inc.** (August - November 2025, remote).

## Project Overview
This project follows a complete NGS workflow, from raw reads to variant interpretation, to identify candidate non-synonymous SNPs and study their predicted effects on protein function.

- **Dataset:** NCBI BioProject PRJNA1086561 (Illumina HiSeq 2500, Navin Lab)
- **Analysed sample:** SRR33505761
- **Reference:** Human chromosome 19 (NC_000019)

## Workflow
1. **Data retrieval:** NCBI SRA
2. **Quality control and assembly:** FastQC, Cutadapt, SPAdes, QUAST (Galaxy)
3. **Read alignment:** Geneious Mapper (chromosome 19)
4. **Genome annotation:** reference-guided annotation of genes, CDS, exons, ncRNA and regulatory regions
5. **Variant calling and effect prediction:** SNPs and InDels, missense and splice-site effects, 100-kb intervals
6. **Data cleaning and visualization:** Tableau, Excel, ClustVis

## Key Results
- Annotated features on chromosome 19: 2,641 genes, 7,522 CDS, 7,071 regulatory elements
- Variants called and annotated for effect on genes and proteins
- Heatmaps of polymorphism type, gene and protein effect (ClustVis)

## Repository Contents
| Folder | Description |
|---|---|
| `docs/` | Final presentation (PDF) |
| `reports/` | Module-wise methods and results |
| `data/` | Cleaned variant table |
| `figures/` | Key figures from the analysis |

## Tools
Galaxy, FastQC, Cutadapt, SPAdes, QUAST, Geneious, Tableau, ClustVis, Excel

## Limitations
Analysis was performed on a single sample and restricted to chromosome 19, so findings are exploratory and not clinical conclusions.

## Author
**Khansa Rubab**
Bioinformatics | Islamabad, Pakistan
LinkedIn: https://www.linkedin.com/in/khansa-rubab-87a16841b/
