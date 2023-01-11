# powassan-genomics
In this project we aim to understand evolution and spread of Powassan virus by sequencing viruses isolated from ticks in the Northeastern United States. 

test test

## Sample collection
Ticks were collected at different locations by colleagues at the Connecticut Agricultural Experiment Station, Colorado State University, Cornell, Maine Medical Center Research Institute, New York State Department of Health, Tufts, and Upstate Medical University.

## Sequencing
### Sequencing platform
* Library construction was performed using an [amplicon-based sequencing approach](https://www.nature.com/articles/nprot.2017.066).
* The Powassan LII primer scheme can be found in the [primer_schemes](primer_schemes) folder
* Sequencing was performed on the NovaSeq, paired-end 150.

### Alignments
* [iVar](https://github.com/andersen-lab/ivar) was used to generate consensus genomes.

### Consensus genomes
* Created using a 75% treshold and at least 10X coverage.
* Uploaded in folder [consensus_sequences](consensus_sequences).

## Nextstrain

Some of our analyses were performed using the [nextstrain](https://nextstrain.org) (`augur`) pipeline. These results can be visualized using `auspice`, accessing the links below:

* [Powassan virus emergence & spread in New England](https://nextstrain.org/community/grubaughlab/powassan-genomics/NE)
* [Powassan virus emergence & spread in North America](https://nextstrain.org/community/grubaughlab/powassan-genomics/All)

---


**Disclaimer.** Please note that this data is still based on work in progress and should be considered preliminary. If you intend to include any of these data in publications, please let us know – otherwise please feel free to download and use without restrictions. We have shared this data with the hope that people will download and use it, as well as scrutinize it so we can improve our methods and analyses. Please contact us if you have any questions or comments – we’ll buy beers for #ResearchParasites that spot flaws and faults in the data and come up with improvements!

**Grubaugh Lab** | Yale School of Public Health (YSPH) | [https://grubaughlab.com/](https://grubaughlab.com/)
