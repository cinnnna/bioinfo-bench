<div style="text-align:center">
<h2>🧬 Bioinfo-Bench: A Simple Benchmark Framework for LLM Bioinformatics Skills Evaluation</h2>
</div>

<a href='https://huggingface.co/datasets/Qiyuan04/bioinfo-bench'><img src='https://img.shields.io/badge/Dataset-Bioinfo%20Bench-4169E1'></img></a>

## Introduction

We introduce **Bioinfo-Bench**, a novel yet straightforward benchmark framework suite crafted to assess the academic knowledge and data mining capabilities of foundational models in bioinformatics. Bioinfo-Bench systematically gathered data from three distinct perspectives: knowledge acquisition, knowledge analysis, and knowledge application, facilitating a comprehensive examination of LLMs in the field of Bioinformatics.

## Bioinfo-Bench-qa

The questions are vary from *10* Bioinformatics domain, referring to the scope of Journal [bioinformatics](https://academic.oup.com/bioinformatics/pages/instructions_for_authors#Scope).

<ul>
    <li>Genome analysis</li>
    <li>Sequence analysis</li>
    <li>Phylogenetics</li>
    <li>Structural bioinformatics</li>
    <li>Gene expression</li>
    <li>Genetic and population analysis</li>
    <li>Systems biology</li>
    <li>Data and text mining</li>
    <li>Databases and ontologies</li>
    <li>Bioimage informatics</li>
</ul>

## Bioinfo-Bench-seq

The system prompt are as follows:

```plain
You are given a nucleotide sequence that was originally a valid RNA. Exactly one error has been introduced randomly. Your task is to identify the type of error applied. Possible error types include:
- Reordering of existing bases
- Deletion of one or more bases
- Addition of an extra base (e.g., U)
- Replacement of one base with another
Choose the most appropriate error type from the options.
```
