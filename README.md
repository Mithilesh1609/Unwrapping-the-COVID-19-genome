# Unwrapping-the-COVID-19-genome

- Here we will try to answering some of the questions of **bio-informatics** in regards to the recent panademic outbreak of **Corona virus(COVID-19)**, from a **non-medical background person's perspective**. 
Every analysis presented here is based on the stuff I learnt and understood (or felt that I actually understood) about **the genomes from the internet**.

## How to run?
- I have used kaggle kernal for running the code, you can use that or jupitar notebook or any editor like pycharm or atom or visual studio code.
- for kaggle just create new notbook and copy the given .py file and add data there from links given in dataset.md file, then select GPU instaed of null in preference section for fast execuastion.

## Acknowledgement

## Work-Flow of the python code.
- Basic Context
- Comparison of composition of genomes
  - Oligonucleotide composition
  - GC Content
- Proteins & Amino Acids
  - Protein Strands by genome 
  - Amino Acids Distribution
  - Finding the ORFs
  - Summary of Protein Sequences
- Sequence Alignment
- Pairwise Sequence Alignment
- Genome Sequence Similarity
- Generating a Phylogenetic Tree
- Clustering all COVID-19 patients' genomes
- Conclusions

## Basic Context

- First Question comes to our mind is **what is genome?**
  - [Genomes](https://en.wikipedia.org/wiki/Genome) are considered to be **genetic material of any organism**. It consists of **[DNA](https://en.wikipedia.org/wiki/DNA)(or [RNA](https://en.wikipedia.org/wiki/RNA))** which in turn can be considered as the **blueprints of any organism's origin.**

- How to **study Genomes?**
   ![](image/genome.png)
  - A genome consists of a **sequence of nucleotides** that together make up all the chromosomes of any organism. These nucleotides are the basic building blocks of DNA and RNA.
  - A DNA genome has 4 types of base nucleotides -
    - **Adenine** also represented as A,
    - **Thymine** represented as T,
    - **Guanine** represented as G and
    - **Cytosine** represented as C.
  
In RNA genome, the Thymine nucleotide is replaced with what is known as Uracil represented as U.
In short, **any genome sequence is basically a combination of all these [nucleotide](https://en.wikipedia.org/wiki/Nucleotide) in some order.**


- Obevise question comes to our mind is that **"Can one find a cure for COVID-19 by studying the genomes?"**

  - Not sure, as the molecular biology has not really been my field of study (never liked Biology tbh) but also because its a very vast subject where to confirm on a single hypothesis also takes months/years of evaluation and testing. 

  - Having said that, the whole purpose of **this analysis is to help the ones who actually understand molecular biology get some data-driven insights** to be able to preapare **a RNA vaccine at the earliest**.
