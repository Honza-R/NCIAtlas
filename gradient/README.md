NCIAtlas Gradients
==================

For selected methods, we also provide total energies and gradients calculated for all systems and their constituent monomers.

These data are stored in extended .xyz files with three additional columns containing the Cartesian gradient. The header contains the system name, charge and total electronic energy. The dimer is labeled "_ab", "_a" and "_b" are the corresponding monomers.

The units used are kcal/mol for energy and Angstroms for coordinates.

Methods
-------

So far, there is only one DFT method available:

- ωB97M-D3BJ/def2-TZVPPD - we used this data for training of the [PM6-ML](https://github.com/Honza-R/mopac-ml) hybrid SQM/ML method
