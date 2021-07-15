# A Semi-Automatic Semantic Consistency-Checking Method for Learning Ontology from Relational Database (CC4LO-RDB)

**Introduction**

This is a semi-automatic semantic consistency-checking method for learning ontology from RDB, in which the graph-based intermediate model is leveraged to represent the semantics of RDB and the specifications of learned ontologies.
- The graph-based intermediate model is encoded by SMV program.
- The specifications of learned ontologies is formalized by CTL formula.

This code could be ran [nuXmv](https://nusmv.fbk.eu/) by using model chcker to verify whether the learned ontolgies satisfy the RDB model by excuting the following commands:
1. read_model -i Mini_University.smv
2. flatten_hierarchy
3. encode_variables
4. build_model
5. check_fsm
6. check_ctlspec

**BibTex**

@article{info12050188,
author = {Ma, Chuangtao and Molnár, Bálint and Benczúr, András},
title = {A Semi-Automatic Semantic Consistency-Checking Method for Learning Ontology from Relational Database},
journal = {Information},
volume = {12},
year = {2021},
number = {5},
article-number = {188},
issn = {2078-2489},
doi = {10.3390/info12050188}
}
