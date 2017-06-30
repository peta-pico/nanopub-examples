ChEMBL HCLI Dataset Descriptions as Nanopublications
====================================================

These are examples of nanopublications extracted from the
[HCLI specification](https://www.w3.org/TR/hcls-dataset/#appendix_1).

The nanopublication [hcls-chembl](hcls-chembl.trig) introduces the dataset at
the **summary** level, by establishing the following identifiers and
cryptographic elements:

- It introduces the identifier of the dataset at the summary level:
  `http://rdf.ebi.ac.uk/chembl/chembl`
- It introduces the public key of the entity authorized to announce new versions
  and metadata updates: `MIIBtzCCASwGByqGSM44...`
- It establishes an immutable and verifiable identifier (Trusty URI) for this
  nanopublication introducing the identifier and its metadata:
  `http://purl.org/np/RAq20KleadvIv-ssT5lXwdEUbpCy_yYDysucuQFSnEqpI`
- And it contains a digital signature of the whole nanopublication with the
  public key mentioned above:
  `MCwCFBMHVzEhDKCvf610NaHUPPPr2DlyAhQ27N5l1p/OccAN3gZLsqOs+AXFmQ==`

The nanopublication [hcls-chembl17](hcls-chembl17.trig) introduces the dataset
at the **version** level, by establishing the following identifiers and
cryptographic elements:

- It introduces the identifier of a version of the given dataset:
  `http://rdf.ebi.ac.uk/chembl/chembl17`
- It introduces the public key of the authorized entity (the same as above).
- It establishes an immutable and verifiable identifier (Trusty URI) for this
  nanopublication introducing the identifier and its metadata:
  `http://purl.org/np/RAVQdST3ofQbJOLBFxWkyqXnQ0Hnfwtejj5mJfgxNODFg`
- And it contains a digital signature of the whole nanopublication with the
  public key mentioned above:
  `MCwCFGKkFLan7feO11hbTqEAzuGV1YsRAhQ1/nBjYto3qIz1SdHR+HvXAa4SlA==`

The nanopublication [hcls-chembl17db](hcls-chembl17db.trig) introduces the
dataset at the **distribution** level, by establishing the following identifiers
and cryptographic elements:

- It introduces the identifier of a distribution of the given version of the
  given dataset: `http://rdf.ebi.ac.uk/chembl/chembl17db`
- In addition to the levels above, it also introduces a direct download URL,
  which has been made immutable and verifiable by a Trusty URI:
  `ftp://ftp.ebi.ac.uk/pub/databases/chembl/ChEMBLdb/releases/chembl_17/chembl_17_mysql.tar.gz?FALgwCA0igFio7SskCQIMpEZIuL2fxAsP6GccWi2MI8Zs`
- It introduces the public key of the authorized entity (the same as above).
- It establishes an immutable and verifiable identifier (Trusty URI) for this
  nanopublication introducing the identifier and its metadata:
  `http://purl.org/np/RAlga593_MtNr4N2TJ2SZ4Trk_6VtLCd9_QoB16qo4QUc`
- And it contains a digital signature of the whole nanopublication with the
  public key mentioned above:
  `MCwCFEZHY/Md2tmJGQ0gfEpBUwWut2OiAhRf0s2YWW5nnr7L2qsWu8b/uZF72g==`
