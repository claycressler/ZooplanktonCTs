# Zooplankton cattle tank data
---

Data from cattle tank experiments investigating the indirect effects of fish kairomones on zooplankton community composition.

## Description of the data and file structure

There are two data files: "Cattle_tank_experiment_species_density_data.csv" and "Cattle_tank_experiment_NMDS_data.csv"

"Cattle_tank_experiment_species_density_data.csv" contains the density estimates of each taxon for each tank in each treatment in each experiment. Column headings are:
Exp (column A): the cattle tank experiment, numbered CT1-CT4
Tank (column B): the cattle tank number, numbered 1-24
Treatment (column C): the experimental treatments, which varied with Exp. 
- For CT1, the treatments are C (control, no-fish treatment), N (notonectid, an invertebrate predation treatment), and F (fish treatment)
- For CT2, the treatments are C (control treatment), M (midge, an invertebrate predation treatment), and F (fish treatment)
- For CT3, the treatments are C (control treatment) and F (fish treatment)
- For CT4, the treatments are C (control treatment), C-P (control treatment with added phosphorus), K (fish treatment), and K-P (fish treatment with added phosphorus)
AbbrvTreat (column D): collapsing all treatments into either Fish or NoFish. Treatments with invertebrate predators were treated as NoFish treatments for the analysis.
Taxa (columns E-T): densities for each taxa in each tank. If a taxon was not observed in a particular experiment (e.g., D.dentifera in CT1), its density is blank (NA) rather than 0.

"Cattle_tank_experiment_NMDS_data.csv" contains the first three NMDS values for each tank in each treatment (fish vs. non-fish) in each experiment, following non-metric multidimensional scaling (NMDS) of the density data. 

## Sharing/Access information

There are no links to other publicly accessible locations of the data, and the data was not derived from any other sources.

## Code/Software

Not applicable.