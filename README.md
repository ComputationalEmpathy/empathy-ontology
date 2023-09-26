# Computational Empathy Ontology
This repository presents an ontology defining the concept we call "computational empathy". This regards a herarchy of sub-concepts for understanding perceptions of empathy in computational systems. In order to enable interoperability with a wide range of knowledge-based systems, the ontology is implemented in Web Ontology Language (OWL).

Empathy is a complex construct, and this ontology provides a formal representation of its facets. Rooted in a qualitative analysis and knowledge engineering process using grounded theory, the ontology formalizes empathy for interactive agents. 

The Empathy Ontology may aid researchers and practitioners in understanding, assessing, and implementing computational empathy. It standardizes discussing and representing empathy in computational systems. The Empathy Ontology finds applications in, e.g., Human-Computer Interaction, Artificial Intelligence, virtual agents, and social robots.

![Empathy Ontology](https://github.com/ComputationalEmpathy/empathy-ontology/blob/f9af1c7ebc78cf088df2d85e158f7dc05051015d/empathy_ontology.png).

## Taxonomy and Dimensions

The Empathy Ontology structures concepts hierarchically. Primary dimensions include:

- Perceive
- Act
- Manifest
- Theory_of_mind
- Ratification
- Interpersonal

These encompass sub-dimensions, capturing hierarchical relationships.

## Ontology Overview

- Ontology IRI: https://github.com/ComputationalEmpathy/empathy-ontology/blob/c84e5761cdd4029fa6f38b716ca07c2477b2042c/empathy-ontology.owl
- Class count:	118	
- Object property count:	17
- SubClassOf:	111
- SubObjectPropertyOf:	16	
- ObjectPropertyDomain:	16	
- ObjectPropertyRange:	17

## Explore the ontology in open-source ontology editor - Protege

* Download the [empathy-ontology](https://github.com/ComputationalEmpathy/empathy-ontology/blob/c84e5761cdd4029fa6f38b716ca07c2477b2042c/empathy-ontology.owl)
* Download Protege: https://protege.stanford.edu/
* Install the OWLViz plugin for class hierarchy visualization: https://protegewiki.stanford.edu/wiki/OWLViz

* Open the .owl file in Protege

* Explore: Classes, Object Properties and Data Protperties

## Run in ontology reasoner

* Ontology reasoner: BaseVISor
* BaseVISor 2.0.2 is licensed for academic and research use free of charge; all other uses require a commercial license at VIStology, Inc.
* Supported syntaxes: RDF/XML, OWL/XML, All OWL API
* Supported reasoning services: realisation, classification, satisfiability, conjunctive query answering, entailment, consistency.
* Creators of BaseVISor: VIStology, Inc.
* More info: https://www.vistology.com/products/

Create a .bvr file according to the BaseVISor documentation, and do the following: 
  * Add relativePath="ontology.owl" and set it to the path of the ontology in your local drive.
  * Run the BaseVISor executable with your .bvr file.
