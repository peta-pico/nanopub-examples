Introducing ChEMBL Dataset Identifiers with HCLI and Nanopublications
=====================================================================

These are examples of nanopublications extracted from the
[HCLI specification](https://www.w3.org/TR/hcls-dataset/#appendix_1).

The nanopublication [hcls-chembl](hcls-chembl.trig) introduces the dataset at
the **summary** level, by establishing the following identifiers and
cryptographic elements:

- It introduces the identifier of the dataset at the summary level:
  `http://rdf.ebi.ac.uk/chembl/chembl`
- It introduces the public key of the entity authorized to announce new versions
  and metadata updates: `MIIBtzCCASwGByqGSM44...`
- It contains a digital signature of the whole nanopublication created with the
  public key mentioned above:
  `MCwCFBMHVzEhDKCvf610NaHUPPPr2DlyAhQ27N5l1p/OccAN3gZLsqOs+AXFmQ==`
- And it finally establishes an immutable and verifiable identifier (Trusty URI)
  for the whole nanopublication including the identifier, its metadata, the
  public key, and the signature:
  `http://purl.org/np/RAq20KleadvIv-ssT5lXwdEUbpCy_yYDysucuQFSnEqpI`

The nanopublication [hcls-chembl17](hcls-chembl17.trig) introduces the dataset
at the **version** level:

- It introduces the identifier of a version of the given dataset:
  `http://rdf.ebi.ac.uk/chembl/chembl17`
- It introduces the public key of the authorized entity (the same as above).
- It contains a digital signature of the whole nanopublication by the
  authorized entity.
- It establishes an immutable and verifiable identifier (Trusty URI) for the
  whole nanopublication:
  `http://purl.org/np/RAVQdST3ofQbJOLBFxWkyqXnQ0Hnfwtejj5mJfgxNODFg`

The nanopublication [hcls-chembl17db](hcls-chembl17db.trig) introduces the
dataset at the **distribution** level:

- It introduces the identifier of a distribution of the given version of the
  given dataset: `http://rdf.ebi.ac.uk/chembl/chembl17db`
- In addition to the levels above, it also introduces a direct download URL,
  which has been made immutable and verifiable by a Trusty URI:
  `ftp://ftp.ebi.ac.uk/pub/databases/chembl/ChEMBLdb/releases/chembl_17/chembl_17_mysql.tar.gz?FALgwCA0igFio7SskCQIMpEZIuL2fxAsP6GccWi2MI8Zs`
- It introduces the public key of the authorized entity (the same as above).
- It contains a digital signature of the whole nanopublication by the
  authorized entity.
- It establishes an immutable and verifiable identifier (Trusty URI) for the
  whole nanopublication:
  `http://purl.org/np/RAlga593_MtNr4N2TJ2SZ4Trk_6VtLCd9_QoB16qo4QUc`

The nanopublication [hcls-chembl17rdf](hcls-chembl17rdf.trig) introduces a
second **distribution** of the dataset:

- It introduces the identifier of another distribution:
  `http://rdf.ebi.ac.uk/chembl/chembl17rdf`
- It also introduces a direct download URL as a Trusty URI:
  `ftp://ftp.ebi.ac.uk/pub/databases/chembl/ChEMBL-RDF/17.0/chembl_17.0_molecule.ttl.gz?FAc-CrwWuwrZOq5aNPp5dEb1FaGkRuj6GnVLR9erjjx5U`
- It introduces the public key of the authorized entity (the same as above).
- It contains a digital signature of the whole nanopublication by the
  authorized entity.
- It establishes an immutable and verifiable identifier (Trusty URI) for the
  whole nanopublication:
  `http://purl.org/np/RA5twh0DiuwjJH3FOFis-TToyrV1CKgYJZGVttrTRFUhM`

