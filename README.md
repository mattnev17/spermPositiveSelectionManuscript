# spermPositiveSelectionManucsript
Code for analysing TwinsUK sperm and blood NanoSeq data from 'Sperm sequencing reveals extensive positive selection in the male germline'

## Data Processing
Sequencing data was processed using the NanoSeq scripts at https://github.com/cancerit/NanoSeq. Following that the following two Rmd scripts in dataProcessing are used to generate all main data files used for results and plotting:
- `RE_nanoseq.Rmd` for processing sperm and blood restriction enzyme (RE) genome NanoSeq data
- `targ_exome_nanoseq.Rmd` for processing sperm targeted and exome NanoSeq data

## Plotting
Code to generate all figures is found in 
- `TwinsUK_sperm_figures.Rmd`

## Data
### Sequencing data
Raw sequencing data will be available on the European Genome–Phenome Archive, accession number TBD.
### Publically available data
Input files for plotting that are publically shareable are available in `data` folder.
### Controlled access data
Input files for plotting that cannot be shared publically are accessible only through TwinsUK, as specified below:

*Additional individual-level data are not permitted to be publicly shared or deposited due to the original consent given at the time of data collection, where access to these data is subject to governance oversight. All data access requests are overseen by the TwinsUK Resource Executive Committee (TREC). For information on access to these genotype and phenotype data and how to apply, see https://twinsuk.ac.uk/resources-for-researchers/access-our-data/.*

