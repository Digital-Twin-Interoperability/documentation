# Documentation

This repo serves as a central directory for documentation related to the DT-Interoperability project at JPL.

## FAQ

#### What is the Spatial Web? What is HSML?
- "The Spatial Web" is synonymous with "Web 3.0," believed to be the next revolution in how the worldwide web works.
  - Think: as the internet is integrated with everything from rockets to refrigerators, the web now extends far beyond just your computer monitor. How can we make all of these devices communicate with one another in harmony?
- In the same way HTML was created by scientists in the 1980s to standardize how web servers display content to users, HSML (HyperSpace Modeling Language) seeks to be the common standard through which all devices -- from smart glasses to self-driving cars -- send and receive information to one another.
  - **Read more:** https://www.amazon.com/Spatial-Web-connect-machines-transform/dp/0578562960 (we have a free copy in the lab!)

#### Why are we using HSML?
- We use HSML to pass information between different simulation platforms -- Unity, Unreal, and Omniverse -- to enable real-time collaboration between users across all three.
  - Think of it like a video game: you're in Unity controlling your rover, and I'm in Omniverse controlling my rocket.
  - This lets us collaboratively simulate, reducing risks of errors (which saves us money, time, and more.)
- **Fact:** For each pound (in materials, machinery, etc.) sent to the moon, the cost is approximately **$1,000,000 USD**.

#### What are we missing?
- **Real-time Physics Collaboration:** Currently, objects in Engine A (ex. Unity) cannot collide with objects in Engine B (ex. Omniverse.)
  - Fix: designate one party in the simulation as the "host." For the duration of the simulation, his/her platform's physics engines will process every collision, and send the relevant outcomes (ex. new positional data after being pushed around) to all other parties' platforms.
- **AI-powered Automation:** A plugin has to be hand-written to integrate each platform into the HSML approach.
  - Creating an AI agent that can generate this plugin for you would enable more rapid adoption across the aerospace industry (and further.)
 
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

## HSML Web App

See README here: https://github.com/Digital-Twin-Interoperability/HSML-Form-Website/blob/main/README.md

**Note:** the ``rework`` branch is most up-to-date.

## Business Logic Plugin Scripts

![Script Breakdown](https://github.com/Digital-Twin-Interoperability/documentation/blob/main/scriptBreakdown.jpg?raw=true)
