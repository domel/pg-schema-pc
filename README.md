# PG-Schema for Property Constraints

**PG-Schema-PC** is an extension of the PG-Schema formalism designed to specify structural constraints in property graph data models. Property graphs are commonly used to represent richly annotated and interconnected data; however, their flexible nature often lacks robust schema support. PG-Schema-PC addresses this by enabling the definition of:

- alternative groupings of properties,
- cardinality and multiplicity constraints,
- value-level conditions over property values.

This repository provides a formal grammar for PG-Schema-PC written in Extended Backus–Naur Form (EBNF), alongside visual representations in the form of railroad diagrams to facilitate comprehension and practical adoption.

## Repository Structure

```
.
├── CITATION.cff         # Citation metadata in CFF format
├── LICENSE              # Open-source license (MIT)
├── pg-schema-pc.ebnf    # Abstract grammar specification in EBNF
└── rr-diagrams.html     # Visual grammar representation (railroad diagrams)
```

## Online Access

The grammar and its diagrams are also available online:

🔗 [Railroad Diagrams](https://domel.github.io/pg-schema-pc/rr-diagrams.html)

## Citation

If you use this software or grammar in your work, please cite it using the following metadata:

```yaml
Tomaszuk, D., & Labra Gayo, J. E. (2025). PG-Schema for Property Constraints (Version 0.1) [Software]. https://doi.org/10.5281/zenodo.16729164
```

Alternatively, use the metadata provided in the [`CITATION.cff`](./CITATION.cff) file.

## Authors

- [Dominik Tomaszuk](https://orcid.org/0000-0003-1806-067X), University of Bialystok  
- [Jose Emilio Labra Gayo](https://orcid.org/0000-0001-8907-5348), University of Oviedo

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Keywords

`PG-Schema`, `Property Graphs`, `Schemas`, `Property Constraints`, `Graph Databases`

## Badges

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16729164.svg)](https://doi.org/10.5281/zenodo.16729164)
