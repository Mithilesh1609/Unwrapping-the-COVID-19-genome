# Unwrapping-the-COVID-19-genome

- Here we will try to answering some of the questions of **bio-informatics** in regards to the recent panademic outbreak of **Corona virus(COVID-19)**, from a **non-medical background person's perspective**. 
Every analysis presented here is based on the stuff I learnt and understood (or felt that I actually understood) about **the genomes from the internet**.

## How to run?
- I have used **kaggle kernal** for running the code, you can use that or **jupyter notebook** or any editor like **pycharm or atom or visual studio code**.
- For kaggle just create new notbook and copy the given **Unwrapping the COVID-19 genome.ipynb** file and Add data there from links given in **dataset.md** file, then select **GPU** instaed of null in preference section for fast execuastion.


## Acknowledgement
I am very thankful to Allen Institute For AI for providing wonderful [dataset](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge).

# Conclusions

- Based on the oligonucleotide compositions, all the genomes from **coronaviridae family** show similar composition (trinucleotide and tetranucleotide composition)
- Based on GC content, the composition of **Hedgehog infected Corona virus** is closely similar to **COVID-19 genome's GC content**.
- Judging by the number of **protein strands**, the count in COVID19's genome is very close to those found in **Bat infected with SARS like corona virus**.
- If you filter down some of the categories in the plotly-plot of distribution of amino acids, you'll see the percentage of amino acids in COVID-19's genome closely match to those of MERS, Civet infected with SARS like CoV, Camel with alpha CoV and Malaria except for some and low high contents among L (Leucine), P (Proline) and T (Threonine) amino acids.
- Checking by the generated Phylogenetic tree, the genomes of COVID-19 and malaria virus show the maximum similarity. Perhaps this also explains why there's a lot of buzz on the news and internet about trying [Hydroxycholorquine](https://en.wikipedia.org/wiki/Hydroxychloroquine) and [anti-retroviral drugs](https://www.deccanherald.com/city/top-bengaluru-stories/coronavirus-hiv-anti-retroviral-drugs-to-be-used-for-covid-19-treatment-814534.html) which happen to be the medicines for malaria and HIV viruses, respectively.
- Of all the genomes of COVID-19 infected patients avaialable on Kaggle, some patients show similar traits when clustered based on their genome sequence similarity.I really don't know how helpful this would be but if something works or had worked for a patient, then same should also work for patients in the same cluster.

**Image of Hylogenetic Tree**

![](image/output.png)
