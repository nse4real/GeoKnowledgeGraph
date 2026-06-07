# schema/

Graph schema documentation and data model diagrams.

## Files

| File | Description |
|---|---|
| `graph_schema.md` | Full node labels, relationship types, and property definitions |
| `data_model_diagram.png` | Visual property graph model diagram |

## Graph Model Overview

The GeoKnowledgeGraph models 5 node types:
- `:Survey` — Seismic acquisition surveys (2D/3D/4D)
- `:Well` — Drilled wells with UWI identifiers
- `:Formation` — Geological formations and stratigraphic units
- `:Operator` — Operating companies (IOC/NOC/Independent)
- `:Basin` — Sedimentary basins and geographic regions

See `graph_schema.md` for full property definitions and relationship types.
