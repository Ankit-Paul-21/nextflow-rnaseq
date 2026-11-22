# RNA-seq Nextflow Pipeline

A modular, reproducible bulk RNA-seq analysis pipeline
developed using Nextflow DSL2.

## Objectives

To implement an end-to-end RNA-seq upstream processing
workflow, from raw sequencing reads to gene-level
expression quantification.

## Workflow

1. Initial quality control using FastQC
2. Adapter trimming using Trim Galore
3. Post-trimming quality control
4. QC report aggregation using MultiQC
5. Reference genome indexing using HISAT2
6. Splice-aware read alignment using HISAT2
7. BAM sorting and indexing using SAMtools
8. Gene-level quantification using featureCounts

## Test Dataset

GSE52778 - Human Airway Smooth Muscle Transcriptome
Changes in Response to Asthma Medications.

Organism: Homo sapiens

Experimental comparison:
Untreated vs Dexamethasone-treated

## Workflow Engine

Nextflow DSL2

## Project Status

Under development.