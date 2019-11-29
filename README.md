# Energy States and Costs Scheduling - Data

This repository contains the data (instances, experiment results) for the scheduling problem with energy states and costs studied in [\[Benedikt2020a\]](#Benedikt2020a).
The source codes are available in [src repository](https://github.com/CTU-IIG/EnergyStatesAndCostsScheduling).

## Data filesystem structure

The root directory of the repository is called *root data directory*.
Its structure is standardized in the following way

- `dataset-generators-prescriptions` - the prescriptions for the dataset generators.
- `datasets` - the generated datasets from the prescriptions.
- `experiments-prescriptions` - the prescriptions for the experiments.
- `results` - the results of the experiments.

## Data corresponding to research articles

### Benedikt2020a

The referenced article contains 5 datasets

Dataset | Generator prescription
--- | ---
PRELIM | `benedikt2020a_prelim`
MEDIUM-NOSBY | `benedikt2020a_medium_nosby`
MEDIUM-TWOSBY | `benedikt2020a_medium_twosby`
LARGE-NOSBY | `benedikt2020a_large_nosby`
LARGE-TWOSBY | `benedikt2020a_large_twosby`

and 3 experiments

Experiment | Experiment prescription | Result tables in Benedikt2020a
--- | --- | ---
Preliminary CP experiments | `benedikt2020a_prelim` | 1
Medium datasets | `benedikt2020a_medium` | 2
Large datasets | `benedikt2020a_large` | 3

## License

[MIT license](LICENSE.txt)

## Authors

Please see file [AUTHORS.txt](AUTHORS.txt) for the list of authors.

## References

[\[Aghelinejad2017a\]](https://doi.org/10.1080/00207543.2017.1414969) MohammadMohsen Aghelinejad, Yassine Ouazene & Alice Yalaoui (2018) Production scheduling optimisation with machine state and time-dependent energy costs, International Journal of Production Research, 56:16, 5558-5575, DOI: 10.1080/00207543.2017.1414969

<a name="Benedikt2020a">[\[Benedikt2020a\]](https://www.researchgate.net/publication/337781297_Power_of_Pre-Processing_Production_Scheduling_with_Variable_Energy_Pricing_and_Power-Saving_States)</a> Ondřej Benedikt, István Módos & Zdeněk Hanzálek (2020) Power of Pre-Processing: Production Scheduling with Variable Energy Pricing and Power-Saving States, CPAIOR2020

## <a name="citing"></a>Citing

TODO: