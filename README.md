# Consistency checking for ontology learning from Relational Database (CC4OL-RDB)

This is a graph-based intermediate model that represent the semantics of RDB and the specifications of learned ontologies.
- The graph-based intermediate model is encoded by SMV program.
- The specifications of learned ontologies is formalzied by CTL formula.

This model could be ran [nuXmv](https://nusmv.fbk.eu/) by using model chcker to verify whether the learned ontolgies satisfy the RDB model by excuting the following commands:
1. read_model -i Mini_University.smv
2. flatten_hierarchy
3. encode_variables
4. build_model
5. check_fsm
6. check_ctlspec


