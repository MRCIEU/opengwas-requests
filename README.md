# Data requests for OpenGWAS

The [OpenGWAS database](https://gwas.mrcieu.ac.uk) is constantly growing, but there may be studies that users have generated or need to include in their analyses that have not yet been incorporated.

We currently import new data in the following ways:

- Automatically detecting newly deposited data in the EBI GWAS summary database and importing it
- Manually add new data batches that EBI do not take on an ad hoc basis

Note that many datasets deposited in EBI do not have the minimum requirements to be included in this database. Those minimum requirements are:

- Effect size and standard error OR effect size and p-value
- Effect allele
- Non-effect allele
- Chromosome
- Position
- Genome build

Please use the [Issues page](https://github.com/MRCIEU/igd-data-requests/issues) to make requests for data to be added to the database, providing links to the original source where possible.

Please also keep in mind that this database is updated on a voluntary basis and time pressures might lead to delays for the team to respond to data requests. Making it as easy as possible for us to source and upload the data is appreciated.

Internal IEU users can add studies using a convenient R package: https://github.com/MRCIEU/GwasDataImport
