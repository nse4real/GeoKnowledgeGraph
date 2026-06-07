# pipeline/

Python data pipeline components for GeoKnowledgeGraph.

## Files

| File | Description |
|---|---|
| `airflow_dag.py` | Apache Airflow DAG: end-to-end CSV to Neo4j metadata-driven ingestion pipeline |
| `neo4j_loader.py` | Class-based Python Neo4j connection and query utility |
| `requirements.txt` | Python dependencies (neo4j, apache-airflow, pandas) |

## Setup

```bash
pip install -r requirements.txt
```

Configure Neo4j connection via environment variables:
```bash
export NEO4J_URI=bolt://localhost:7687
export NEO4J_USER=neo4j
export NEO4J_PASSWORD=your_password
```
