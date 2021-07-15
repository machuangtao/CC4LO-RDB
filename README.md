# Consistency Checking for Learning Ontology from Relational Database (CC4OL-RDB)

**Introduction**

This is a graph-based intermediate model that represent the semantics of RDB and the specifications of learned ontologies.
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

@Article{info12050188,
AUTHOR = {Ma, Chuangtao and Molnár, Bálint and Benczúr, András},
TITLE = {A Semi-Automatic Semantic Consistency-Checking Method for Learning Ontology from Relational Database},
JOURNAL = {Information},
VOLUME = {12},
YEAR = {2021},
NUMBER = {5},
ARTICLE-NUMBER = {188},
ISSN = {2078-2489},
DOI = {10.3390/info12050188}
}
