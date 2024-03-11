# ChEMBL_SQL_Tutorial
ChEMBL is the largest, open-access database of bioactive molecules with drug-like properties, maintained by the European Bioinformatics Institute (EBI) of the European Molecular Biology Laboratory (EMBL). This code gives examples of how to navigate the ChEMBL schema to curate a database for your specific research question using SQL.

EMBL already provides great [SQL examples](https://chembl.gitbook.io/chembl-interface-documentation/frequently-asked-questions/schema-questions-and-sql-examples) and [Free online tutorials](https://www.ebi.ac.uk/training/online/courses/embl-ebi-programmatically/chembl-programmatically/) on how to access different EMBL-EBI resources programmatically. This guide is intended to provide a bit more context for SQL beginners and visual guidance for relational database management in ChEMBL.

## First things first
The ChEMBL database is organised in a schema that can be found on the [ChEMBL Schema Page](https://www.ebi.ac.uk/chembl/db_schema). Navigating through the schema allows for the incorporation of data selection criteria and curation of a personalised database with columns of interest.

![ChEMBL_33 Schema from May 31 2023](https://ftp.ebi.ac.uk/pub/databases/chembl/ChEMBLdb/latest/chembl_33_schema.png)

By looking at the ChEMBL schema, discern which information is relevant to your research. Are you interested in compounds and their bioactivity in binding assays? Are you interested in binding site information? Find the column headers of interest and think about how to connect them.

## Getting started

**Step 1:**	Download the `chembl_33_mysql.tar.gz` (Or newest release) from [ChEMBL Downloads Page](https://chembl.gitbook.io/chembl-interface-documentation/downloads)

> [!NOTE]
> This file is 1.6G and may take a while to install depending on your device.

> [!TIP]
> For smaller queries, you may want to use the ChEMBL API instead of downloading the entire database.

**Step 2:** 



# for code use backticks
``
