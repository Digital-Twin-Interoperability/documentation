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
- **[BL Plugin & HSML API](https://github.com/Digital-Twin-Interoperability/hsml_schema/blob/main/docs/BL%20Plugin%20%26%20HSML%20API.docx)**: Logic behind the development of the HSML API and the new BL plugins
- **[HSML Schema Doc](https://github.com/Digital-Twin-Interoperability/hsml_schema/blob/main/docs/HSML%20Schema%20Doc.docx)**: HSML ontology, HSML Classes Tables with the properties from Schema.org & custom properties.
- **[Schema Properties.xlsx](https://github.com/Digital-Twin-Interoperability/hsml_schema/blob/main/docs/Schema%20Properties.xlsx)**: Excel linked to HSML Schema Doc, used to track better the added properties before including them in the doc.
- **[HSML Summary](https://github.com/Digital-Twin-Interoperability/hsml_schema/blob/main/docs/HSML%20Summary.docx)**: Brief summary of HSML Schema
- **[Master Thesis Alicia Sanjurjo](https://github.com/Digital-Twin-Interoperability/hsml_schema/blob/main/docs/Master_Thesis_Alicia_Sanjurjo_345C_Draft_2.pdf)**: Inside the Methods Chapter, the Architecture is explained in detail (HSML Schema, DID:key Method, HSML API + Verification Logic)
- **[MySQL Setup SWID Registry](https://github.com/Digital-Twin-Interoperability/hsml_schema/blob/main/docs/MySQL%20Setup%20SWID%20Registry.docx)**: How to set up MySQL database in any machine
- **[Testing User Manual](https://github.com/Digital-Twin-Interoperability/hsml_schema/blob/main/docs/Testing%20User%20Manual.docx)**: How to conduct testing with the platforms in the Lab with and without the HSML API
- **[Verification Codes Doc](https://github.com/Digital-Twin-Interoperability/hsml_schema/blob/main/docs/Verification%20Codes%20Doc.docx)**: Explains initial development and code of the 3 routers of the HSML API (registration, authentication, authorization)
- **[Feedback Channel](https://github.com/Digital-Twin-Interoperability/hsml_schema/blob/main/docs/Feedback%20Channel.docx)**: Channel & Activities next steps to implement them.
- **[How to Update HSML Schema](https://github.com/Digital-Twin-Interoperability/hsml_schema/blob/main/docs/How%20to%20Update%20HSML%20Schema.docx)**: Explains how to add new custom properties to the hsml.jsonld and document it well along the way.
