# cypher/

This directory contains all Cypher query scripts for the GeoKnowledgeGraph project.

## Files

| File | Description |
|---|---|
| `01_create_constraints.cypher` | Uniqueness constraints and indexes for all node labels |
| `02_load_nodes.cypher` | MERGE statements to load synthetic geoscience node data |
| `03_load_relationships.cypher` | Relationship creation between nodes |
| `04_analytical_queries.cypher` | 10+ analytical Cypher queries for geoscience data exploration |

## Running the Scripts

Run scripts in order (01 → 04) against a running Neo4j instance:

```bash
# Using cypher-shell
cypher-shell -u neo4j -p password < 01_create_constraints.cypher
cypher-shell -u neo4j -p password < 02_load_nodes.cypher
cypher-shell -u neo4j -p password < 03_load_relationships.cypher
```

Or paste directly into Neo4j Browser at http://localhost:7474
