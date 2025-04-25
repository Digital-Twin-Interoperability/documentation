# Documentation

This repo serves as a central directory for documentation related to the DT-Interoperability project at JPL.

## HSML API
##### *(Credit: Alicia Sanjurjo-Barrio)*
### Repo: https://github.com/Digital-Twin-Interoperability/hsml_schema

#### Project Goals
- Design a comprehensive schema for representing spatial information following the Spatial Web's standard.
- Facilitate integration with other modeling standards and systems.
- Ensure compatibility with both physical and virtual representations of objects.
- Support a range of use cases, including digital twins, robotics, and real-time simulations.


#### Repository Contents
- **`docs/`**: Contains the Documentation that facilitates the understanding and implementation of HSML.
- **`examples/`**: Contains example JSON files for different Entity classes.
- **`hsml-context/`**: Contains the hsml.jsonld context file that defines the classes and properties needed.
- **`presentations/`**: Contains the Weekly Presentations by Alicia Sanjurjo.
- **`scripts/`**: Contains Python scripts developed for the Verification and to test with the Kafka server.
- **`swid_generator/`**: Contains the Python CLI tool used to generate the public & private key pair for the DID:key method.

#### Documentation Guide
- **BL Plugin & HSML API**: Logic behind the development of the HSML API and the new BL plugins
- **HSML Schema Doc**: HSML ontology, HSML Classes Tables with the properties from Schema.org & custom properties.
- **Schema Properties.xlsx**: Excel linked to HSML Schema Doc, used to track better the added properties before including them in the doc.
- **HSML Summary**: Brief summary of HSML Schema
- **Master Thesis Alicia Sanjurjo**: Inside the Methods Chapter, the Architecture is explained in detail (HSML Schema, DID:key Method, HSML API + Verification Logic)
- **MySQL Setup SWID Registry**: How to set up MySQL database in any machine
- **Testing User Manual**: How to conduct testing with the platforms in the Lab with and without the HSML API
- **Verification Codes Doc**: Explains initial development and code of the 3 routers of the HSML API (registration, authentication, authorization)
- **Feedback Channel**: Channel & Activities next steps to implement them.
- **How to Update HSML Schema**: Explains how to add new custom properties to the hsml.jsonld and document it well along the way.
