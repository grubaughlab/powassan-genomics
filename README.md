# powassan-genomics
In this project we aim to understand local transmission of Powassan virus by sequencing viruses isolated from *Ixodes scapularis* ticks in the Northeastern United States. 

## Sample collection
Ticks were collected at different locations by colleagues at the Connecticut Agricultural Experiment Station and the Maine Medical Center Research Institute. Metadata and sequencing statistics can be found [here](https://docs.google.com/spreadsheets/d/1vPY7roZUkjlYLiJvrNX6X5KLFuoD-c_5LbVUiRM02KQ/edit?usp=sharing).

## Sequencing
### Sequencing platform
* Library construction was performed using a [metagenomics approach](https://docs.google.com/document/d/1Tm-fABgAUdCHuBHnyW9az5tbEcoQW7AzjXeIdduDy-I/edit), without DNAse treatment.
* Sequencing was performed on the NovaSeq, paired-end 150.

### Alignments
* Geneious Prime was used to process sequence data.
* PCR duplicates were removed using dedupe duplicates remover.
* Sequences were mapped to reference sequence using bowtie2 at high sensitivity.

### Consensus genomes
* Created using a 75% treshold and at least 10X coverage.
* Uploaded in folder [consensus_sequences](consensus_sequences).


**Disclaimer.** Please note that this data is still based on work in progress and should be considered preliminary. If you intend to include any of these data in publications, please let us know – otherwise please feel free to download and use without restrictions. We have shared this data with the hope that people will download and use it, as well as scrutinize it so we can improve our methods and analyses. Please contact us if you have any questions or comments – we’ll buy beers for #ResearchParasites that spot flaws and faults in the data and come up with improvements!
