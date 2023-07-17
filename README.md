# OntoUML Metamodel

The OntoUML Metamodel repository contains the metamodel of the OntoUML language. Unlike the UML profile, this version is independent of UML a presents all concepts officially supported in the language. This metamodel covers the abstract and concrete syntaxes of the language and serves as the reference for all projects in the [OntoUML as a Service (OaaS)](https://ceur-ws.org/Vol-2969/paper29-FOMI.pdf) ecosystem, including its different model serializations.

![](./diagrams/Metamodel%20Summary%20Diagram.png)


## Repository Organization

- `OntoUML Metamodel.vpp`: Visual Paradigm project file containing the developed OntoUML Metamodel.

- `./diagrams`: folder containing all diagrams of the OntoUML Metamodel.


## Related Projects

- [OntoUML Schema](https://github.com/OntoUML/ontouml-schema): the JSON serialization of OntoUML models that supports the exchange of models over HTTP in microservice architectures.

- [OntoUML Vocabulary](https://github.com/OntoUML/ontouml-vocabulary): the Turtle serialization of OntoUML models that supports querying model datasets in knowledge graphs.

- [OntoUML Plugin for Visual Paradigm](https://github.com/OntoUML/ontouml-vp-plugin): a [Visual [Paradigm](https://www.visual-paradigm.com/) plugin that provides OntoUML-specific features and enables access to OaaS services (e.g., export models in the JSON format in compliance with the ontouml-schema).

- [OntoUML JSON2Graph Decoder](https://w3id.org/ontouml/json2graph): a model transformation service from JSON ([ontouml-schema](https://github.com/OntoUML/ontouml-schema)) to a graph format (OntoUML Vocabulary).

- [OntoUML/UFO Catalog](https://github.com/OntoUML/ontouml-models): a FAIR open-source model catalog that contains hundreds of OntoUML and UFO ontologies.


## Contributors

The OntoUML Metamodel is maintained by the [Semantics, Cybersecurity & Services (SCS) Group](https://www.utwente.nl/en/eemcs/scs/) of the [University of Twente](https://www.utwente.nl).

The creators and main contributors of this project include:

- [Tiago Prince Sales](https://orcid.org/0000-0002-5385-5761) [[GitHub]](https://github.com/tgoprince) [[LinkedIn]](https://www.linkedin.com/in/tiago-sales/)
- [Pedro Paulo Favato Barcelos](https://orcid.org/0000-0003-2736-7817) [[GitHub]](https://github.com/pedropaulofb) [[LinkedIn]](https://www.linkedin.com/in/pedro-paulo-favato-barcelos/)
- [Claudenir Fonseca](https://orcid.org/0000-0003-2528-3118) [[GitHub]](https://github.com/claudenirmf) [[LinkedIn]](https://www.linkedin.com/in/claudenirmf/)
