# OntoUML Metamodel

The OntoUML Metamodel is used for the JSON ([OntoUML-Schema](https://github.com/OntoUML/ontouml-schema)) and Graph serializations ([OntoUML Vocabulary](https://github.com/OntoUML/ontouml-vocabulary)) (specified in Turtle).

## Serialization Formats

The OntoUML Model is used as reference for the serialization of OntoUML models in two different formats:

1. The [OntoUML Schema](https://w3id.org/ontouml/schema) defines a JSON Schema message format for the exchange of OntoUML models. This schema is licensed under [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
2. The [OntoUML Vocabulary](https://w3id.org/ontouml/vocabulary) is an implementation of the OntoUML Metamodel in the Web Ontology Language (OWL). This vocabulary supports the serialization, exchange, and publishing of OntoUML models as linked data and is licensed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

## Employment in Projects and Computational Tools

1. The [ontouml-vp-plugin](https://github.com/OntoUML/ontouml-vp-plugin) is a plugin to the [Visual Paradigm](https://www.visual-paradigm.com/) model editor that enables the development of OntoUML models. It is defined under the umbrella of the [OntoUML Server](https://github.com/OntoUML/ontouml-server). By using the plugin a user can export models in the JSON format in compliance with the ontouml-schema.
2. The [OntoUML JSON2Graph Decoder](https://w3id.org/ontouml/json2graph) provides a transformation from data encoded as JSON according to the [ontouml-schema](https://github.com/OntoUML/ontouml-schema) to a graph format (e.g., TTL) in compliance with the OntoUML Vocabulary.
3. The [OntoUML/UFO Catalog](https://github.com/OntoUML/ontouml-models) uses the OntoUML Vocabulary for the TTL serialization of its models. The FAIR Model Catalog for Ontology-Driven Conceptual Modeling Research, short-named OntoUML/UFO Catalog, is a structured and open-source catalog that contains OntoUML and UFO ontology models. It was conceived to allow collaborative work and to be easily accessible to all its users.

## Contributors

The OntoUML Vocabulary is supported by the [Semantics, Cybersecurity & Services (SCS) Group](https://www.utwente.nl/en/eemcs/scs/) from the University of Twente.

The creators and main contributors of this project include:

- [Tiago Prince Sales](https://orcid.org/0000-0002-5385-5761) [[GitHub]](https://github.com/tgoprince) [[LinkedIn]](https://www.linkedin.com/in/tiago-sales/)
- [Pedro Paulo Favato Barcelos](https://orcid.org/0000-0003-2736-7817) [[GitHub]](https://github.com/pedropaulofb) [[LinkedIn]](https://www.linkedin.com/in/pedro-paulo-favato-barcelos/)
