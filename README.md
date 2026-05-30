# tp53-sequence-analysis

<div align="center">

# TP53 Sequence Analysis Pipeline

### Bioinformatics Workflow for TP53 Nucleotide Sequence Characterization

Comprehensive sequence analysis integrating **NCBI BLASTn**, **pairwise alignment**, **multiple sequence alignment (MSA)**, and **phylogenetic characterization** of the **TP53 tumor suppressor gene**.

![Field](https://img.shields.io/badge/Field-Bioinformatics-black)
![Analysis](https://img.shields.io/badge/Analysis-Sequence%20Analysis-black)
![Gene](https://img.shields.io/badge/Gene-TP53-black)
![Status](https://img.shields.io/badge/Status-Completed-success)

</div>

---

## Overview

This repository presents a **bioinformatics workflow for TP53 nucleotide sequence analysis** using **NCBI BLASTn** and related computational tools for sequence identification, similarity assessment, evolutionary interpretation, and conservation analysis.

The study integrates **sequence similarity searching**, **pairwise alignment**, **multiple sequence alignment (MSA)**, and **phylogenetic analysis** to evaluate conservation and biological significance of the **TP53 tumor suppressor gene**.

The project demonstrates practical applications of computational biology tools for molecular sequence characterization and genomic interpretation.

---

# Research Objective

To analyse the **TP53 nucleotide sequence** using **NCBI BLASTn** and associated bioinformatics tools for:

* Sequence identification
* Similarity assessment
* Pairwise sequence alignment
* Multiple sequence alignment (MSA)
* Phylogenetic characterization

---

# Sequence Information

| Parameter                    | Value           |
| ---------------------------- | --------------- |
| **Gene**                     | TP53            |
| **Sequence Type**            | Nucleotide      |
| **Database Used**            | NCBI            |
| **BLAST Tool**               | BLASTn          |
| **MSA Tool**                 | NCBI MSA Viewer |
| **Top Hit Accession Number** | `AM076970.1`    |
| **Species**                  | *Homo sapiens*  |

---

# Workflow

## 1. Sequence Retrieval

The TP53 nucleotide sequence was retrieved and formatted in **FASTA format** for downstream bioinformatics analysis.

### Query Sequence

```text
>Query_TP53_sequence
ATGGAGGAGCCGCAGTCAGATCCTAGCGTCGAGCCCCCTCTGAGTCAGGAAACATTTTCAGACCTATGGAAACTACTTCCTGAAAACAACGTTCTGTCCCCCTTGCCGTCCCAAGCAATG
```

The retrieved sequence served as the query for similarity searching using **NCBI BLASTn**.

<p align="center">
  <img src="figures/tp53_sequence.png" width="700">
</p>

---

## 2. BLASTn Sequence Similarity Analysis

Sequence similarity analysis was performed using **NCBI BLASTn** against nucleotide databases to identify homologous TP53-related sequences.

### BLAST Summary

| Metric           | Result       |
| ---------------- | ------------ |
| Maximum Score    | `486 bits`   |
| Query Coverage   | `95%`        |
| Percent Identity | `100%`       |
| E-value          | `8e-133`     |
| Top Hit          | `AM076970.1` |

### Key Findings

The query sequence demonstrated **highly significant similarity** with multiple **Homo sapiens TP53 sequences**, including:

* TP53 mutant forms
* TP53 beta isoforms
* Tumor suppressor TP53 mRNA sequences

The extremely low **E-value** and **100% identity** confirmed that the query sequence belongs to the **TP53 gene family**.

<p align="center">
  <img src="figures/blast_results.png" width="700">
</p>

---

## 3. Pairwise Alignment Analysis

Pairwise alignment was performed to compare the query sequence against the highest-scoring TP53 sequence.

### Alignment Statistics

| Parameter         | Result           |
| ----------------- | ---------------- |
| Identities        | `263/263 (100%)` |
| Gaps              | `0`              |
| Alignment Quality | Excellent        |

### Interpretation

The alignment demonstrated **complete sequence identity without gaps**, indicating strong conservation and close similarity to known **Homo sapiens TP53 sequences**.

The absence of mismatches and gaps suggests that the analysed region is **highly conserved and biologically important**.

<p align="center">
  <img src="figures/pairwise_alignment.png" width="700">
</p>

---

## 4. Multiple Sequence Alignment (MSA)

Multiple sequence alignment was performed using the **NCBI MSA Viewer** to compare multiple TP53-related sequences simultaneously.

### Major Observations

* Strong sequence conservation across aligned regions
* Very limited sequence variation
* Conserved regions indicate functional importance
* Shared structural and evolutionary similarity observed

### Interpretation

The MSA analysis demonstrated that **TP53 is highly conserved among Homo sapiens sequences**, supporting its critical biological role in **tumor suppression and genomic stability**.

<p align="center">
  <img src="figures/msa_viewer.png" width="700">
</p>

---

## 5. Phylogenetic Analysis

Phylogenetic analysis was performed using the **distance tree generated from BLAST results** to evaluate evolutionary relationships.

### Key Findings

* TP53 sequences clustered closely together
* *Homo sapiens* TP53 sequences formed related branches
* Minimal evolutionary distance observed
* Strong genetic similarity confirmed

### Interpretation

The phylogenetic analysis suggested that **TP53 is evolutionarily conserved**, reflecting its essential role in **cell-cycle regulation and tumor suppression**.

<p align="center">
  <img src="figures/phylogenetic_tree.png" width="700">
</p>

---

# Key Findings

* The TP53 query sequence showed **100% identity** with known *Homo sapiens* TP53 sequences.
* **BLASTn analysis** confirmed highly significant sequence similarity (**E-value = 8e−133**).
* Pairwise alignment demonstrated **perfect conservation with no gaps**.
* **MSA analysis** confirmed highly conserved functional regions.
* Phylogenetic analysis demonstrated **close evolutionary relationships** among TP53 sequences.

---

# Repository Structure

```bash
tp53-sequence-analysis/
│── README.md
│── LICENSE
│
├── data/
├── blast/
├── msa/
├── results/
```

---

# Tools & Technologies

| Category                    | Tool                |
| --------------------------- | ------------------- |
| Database                    | NCBI                |
| Similarity Search           | BLASTn              |
| Multiple Sequence Alignment | NCBI MSA Viewer     |
| Phylogenetic Analysis       | BLAST Distance Tree |

---

## Scientific Relevance

**TP53** is one of the most important **tumor suppressor genes** involved in **DNA repair, apoptosis, genomic stability, and cell-cycle regulation**.

Mutations in TP53 are strongly associated with multiple cancers, making it one of the most extensively studied genes in molecular biology and cancer genomics.

This repository demonstrates the application of **bioinformatics workflows for nucleotide sequence analysis, comparative genomics, and evolutionary interpretation**.

---

## Author

**Ayushi**

Bioinformatics • Computational Biology • Genomics

<div align="center">

### Bioinformatics × Genomics × Sequence Analysis

</div>
