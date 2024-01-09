# Non-Covalent Interactions Atlas

Non-Covalent Interactions Atlas is a collection of computational chemistry data sets of accurate interaction energies in non-covalent complexes covering different classes of interactions in an extended chemical space.

More information is available at the [NCIAtlas website](http://www.nciatlas.org).

The repository is also archived at Zenodo: [![DOI](https://zenodo.org/badge/444723462.svg)](https://zenodo.org/badge/latestdoi/444723462)


## Repository oganization

The core part are the geometries of the systems, in the widespread .xyz format. Each geometry also includes a header with all the information necessary for performing the calculations and the benchmark interaction energy. For many applications, these files are all what is needed. The geometries for each data set are in subdirectories of the [geometries directory](https://github.com/Honza-R/NCIAtlas/tree/main/geometries).

Additional data including components of the benchmark interaction energy and results of other calculations featured in the publications are provided as plain text tables in the [tables directory](https://github.com/Honza-R/NCIAtlas/tree/main/tables). These are also packaged together with geometries in the [packaged_sets directory](https://github.com/Honza-R/NCIAtlas/tree/main/packaged_sets).

All these data are also provided in a structured YAML file used by the [Cuby framework](http://cuby4.molecular.cz/). These files are located in the [dataset_definition_files directory](https://github.com/Honza-R/NCIAtlas/tree/main/dataset_definition_files).

## Data versions

The data provided here are available also at the [NCIAtlas website](http://www.nciatlas.org) and as a supporting information of the individual papers. The data (molecular geometries, computed results) should be the same, but their organization, file names, etc. may differ. This repository aims to provide the data in a structure as consistent as possible across all the data sets.

## DFT-SAPT results

DFT-SAPT interaction energy decomposition data for the D442x10, HB300SPXx10, HB375x10, IHB100x10, R739x5 and SH250x10 data sets contributed by E. Masumian and A. D. Boese are available in the [tables directory](https://github.com/Honza-R/NCIAtlas/tree/main/tables). Two sets of results, computed with DFT-SAPT based on either B3LYP or PBE0 functional, are available for each data set.


## References

### D1200 - London dispersion in an extended chemical space
[J. Řezáč, Phys. Chem. Chem. Phys., 2022, 24, 14780–14793.](https://doi.org/10.1039/D2CP01602H)

### D442x10 - London dispersion in an extended chemical space, 10-point dissociation curves
[J. Řezáč, Phys. Chem. Chem. Phys., 2022, 24, 14780–14793.](https://doi.org/10.1039/D2CP01602H)

### SH250x10 - Sigma-hole interactions
[K. Kříž and J. Řezáč, Phys. Chem. Chem. Phys., 2022, 24, 14794–14804.](https://doi.org/10.1039/D2CP01600A)

### R739×5 - Repulsive contacts in an extended chemical space
[K. Kříž, M. Nováček and J. Řezáč, J. Chem. Theory Comput., 2021, 17, 1548–1561.](https://pubs.acs.org/doi/full/10.1021/acs.jctc.0c01341)

### HB300SPX×10 - Hydrogen bonding extended to S, P and halogens
[J. Řezáč, J. Chem. Theory Comput., 2020, 16, 6305–6316.](https://dx.doi.org/10.1021/acs.jctc.0c00715)

### HB375×10 - Hydrogen bonding in organic molecules
[J. Řezáč, J. Chem. Theory Comput., 2020, 16, 2355–2368.](https://doi.org/10.1021/acs.jctc.9b01265)

### IHB100×10 - Ionic hydrogen bonds in organic molecules
[J. Řezáč, J. Chem. Theory Comput., 2020, 16, 2355–2368.](https://doi.org/10.1021/acs.jctc.9b01265)

### DFT-SAPT results
[E. Masumian and A. D. Boese, J. Chem. Theory Comput. 2024, 20, 30–48](https://doi.org/10.1021/acs.jctc.3c00801)
