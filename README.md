#  Multi-model-median regional means at warming levels for selected indices (CMIP6)

Document multi-model-median regional means at warming levels for selected indices (CMIP6).

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4603428.svg)](https://doi.org/10.5281/zenodo.4603428)

*Mathias Hauser*<sup>1</sup>

<sup>1</sup>Institute for Atmospheric and Climate Science, ETH Zurich, Zurich, Switzerland

## Disclaimer

This data archive is created and maintained in an voluntary effort by its creators. The data are provided without warranty of any kind. Please note that the ownership of all files in the archive remains with the original providers! That means you should still acknowledge the CMIP6 data providers. This work is published under a [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/) license by the authors. If you use the this archive please cite [10.5281/zenodo.4603427](https://doi.org/10.5281/zenodo.4603427).

## Indices

:warning: The multi model median depends on the models that are in the ensemble. A ensemble of opportunity is used here: all available models are included. Only one simulation per model is included.

| Index     | Markdown | csv |
|:----------|:---------|:----|
|TXx|[TXx.md](indices_multi_model_median/md/cmip_indices_multi_model_median_regional_TXx.md)|[TXx.csv](indices_multi_model_median/csv/cmip_indices_multi_model_median_regional_TXx.csv)|
|TNn|[TNn.md](indices_multi_model_median/md/cmip_indices_multi_model_median_regional_TNn.md)|[TNn.csv](indices_multi_model_median/csv/cmip_indices_multi_model_median_regional_TNn.csv)|
|Rx1day|[Rx1day.md](indices_multi_model_median/md/cmip_indices_multi_model_median_regional_Rx1day.md)|[Rx1day.csv](indices_multi_model_median/csv/cmip_indices_multi_model_median_regional_Rx1day.csv)|
|Rx5day|[Rx5day.md](indices_multi_model_median/md/cmip_indices_multi_model_median_regional_Rx5day.md)|[Rx5day.csv](indices_multi_model_median/csv/cmip_indices_multi_model_median_regional_Rx5day.csv)|
|SM_total|[SM_total.md](indices_multi_model_median/md/cmip_indices_multi_model_median_regional_SM_total.md)|[SM_total.csv](indices_multi_model_median/csv/cmip_indices_multi_model_median_regional_SM_total.csv)|
|SM_top|[SM_top.md](indices_multi_model_median/md/cmip_indices_multi_model_median_regional_SM_top.md)|[SM_top.csv](indices_multi_model_median/csv/cmip_indices_multi_model_median_regional_SM_top.csv)|
|CDD|[CDD.md](indices_multi_model_median/md/cmip_indices_multi_model_median_regional_CDD.md)|[CDD.csv](indices_multi_model_median/csv/cmip_indices_multi_model_median_regional_CDD.csv)|

## Used models models

The used models are listed in [data tables](indices_multi_model_median/data_tables/)

## Method

The regional statistics are calculated as follows:

1. calculate the index on the original model grid
2. calculate the area-weighted mean over the AR6 regions
3. calculate anomalies w.r.t. 1850-1900
4. calculate the mean over the years where a warming level is reached (see [cmip_warming_levels](https://github.com/mathause/cmip_warming_levels))
5. calculate the multi model median

## Code
The code will be published in https://github.com/IPCC-WG1 as soon as I have the right to create a repository.

## Changelog

The changelog of the repository can be found under [CHANGELOG.md](CHANGELOG.md).


## License

CMIP TEMPERATURES is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.

A copy of the license is availabe at [LICENSE](LICENSE). If not, see [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).

### CMIP6 Data License Statement

The raw CMIP6 data are licensed under Creative Commons [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0), following the [CMIP6 Terms of Use](https://pcmdi.llnl.gov/CMIP6/TermsOfUse). Note that some models publish the data under a non-commercial license ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)). The license for each particular model dataset can be obtained at the [ESGF CoG portal](https://esgf-node.llnl.gov/search/cmip6) as part of the data citation information.

## Acknowledgment

We thank Urs Beyerle for downloading and curating the CMIP5 and CMIP6 data at the Institute for Atmospheric and Climate Science, ETH Zurich, Zurich, Switzerland.

### CMIP6

We acknowledge the World Climate Research Programme, which, through its Working Group on Coupled Modelling, coordinated and promoted CMIP6. We thank the climate modeling groups for producing and making available their model output, the Earth System Grid Federation (ESGF) for archiving the data and providing access, and the multiple funding agencies who support CMIP6 and ESGF.
