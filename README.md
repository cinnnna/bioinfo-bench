# bioinfo-bench
A SIMPLE BENCHMARK FRAMEWORK FOR LLM BIOINFORMATICS SKILLS EVALUATION
<div style="text-align:center">
<h2>🧬 Bioinfo-Bench: A Simple Benchmark Framework for LLM Bioinformatics Skills Evaluation</h2>
</div>

<a href=' '>< img src='https://img.shields.io/badge/Dataset-Bioinfo%20Bench-4169E1'></img></a >

## Introduction

We introduce **Bioinfo-Bench**, a novel yet straightforward benchmark framework suite crafted to assess the academic knowledge and data mining capabilities of foundational models in bioinformatics. Bioinfo-Bench systematically gathered data from three distinct perspectives: knowledge acquisition, knowledge analysis, and knowledge application, facilitating a comprehensive examination of LLMs in the field of Bioinformatics.

## Bioinfo-Bench-qa

The questions are vary from *10* Bioinformatics domain, referring to the scope of Journal [bioinformatics](https://academic.oup.com/bioinformatics/pages/instructions_for_authors#Scope).

<ul>
    <li><a data-link-id="f70ed163-74fc-4602-af96-97c54443fa55" href="#Genome analysis">Genome analysis</a ></li>
    <li><a data-link-id="67b19e3c-2621-4fb6-897d-31149202a8ca" href="#Sequence analysis">Sequence analysis</a ></li>
    <li><a data-link-id="edd9d779-77ad-4be8-810d-0f358186f65a" href="#Phylogenetics">Phylogenetics</a ></li>
    <li><a data-link-id="837358fc-d4d0-483b-921a-5b2d20a1082b" href="#Structural Bioinformatics">Structural bioinformatics</a ></li>
    <li><a data-link-id="4b54ad37-32f5-4b38-8cb8-02b2447a213c" href="#Gene Expression">Gene expression</a ></li>
    <li><a data-link-id="7fb93deb-f8ab-4f32-a30a-1a3a75cbe8fb" href="#Genetics and Population Analysis">Genetic and population analysis</a ></li>
    <li><a data-link-id="42bdf79f-0721-4ca1-9514-f1169ed2e5a6" href="#Systems Biology">Systems biology</a ></li>
    <li><a data-link-id="ea61a866-5b6b-40ff-9b43-2cd4fa601be4" href="#Data and Text Mining">Data and text mining</a ></li>
    <li><a data-link-id="2d1f0cc8-6505-40bf-a206-299c85f842f2" href="#Databases and Ontologies">Databases and ontologies</a ></li>
    <li><a data-link-id="64e229e2-02be-43f2-a743-d093e9b716a2" href="#Bioimage Informatics">Bioimage informatics</a ></li>
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
