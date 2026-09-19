# Awesome-Model-Based-Systems-Engineering

## Top Model-Based Systems Engineering (MBSE) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on SysML Modeling, Architecture Design, Requirements Traceability, Digital Thread & Complex Systems Engineering*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Model-Based Systems Engineering (MBSE)**. These tools enable teams to design, analyze, and manage complex systems using formal models (SysML, Arcadia, etc.) rather than document-centric approaches—supporting architecture, requirements, interfaces, and verification.



**Examples** include Cameo Systems Modeler, IBM Rhapsody, Capella Cloud, Valispace, GENESYS, Sparx Enterprise Architect, Ansys ModelCenter, PTC Modeler, Innoslate, and Vitech GENESYS (the category leaders).



**Open-source emphasis**: True industrial-grade MBSE tools are limited in the open-source world, but **Eclipse Capella** (with the Arcadia method) stands out as a mature, production-used open solution. **Papyrus**, Python bindings such as **capellambse**, and related modeling frameworks provide additional options. This section highlights the strongest available open resources.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Cameo Systems Modeler (Catia Magic / No Magic)](https://www.3ds.com/)**  

  Industry-leading SysML modeling tool widely used for complex systems architecture, simulation integration, and digital thread (now part of Dassault Systèmes).



- **[IBM Engineering Systems Design Rhapsody](https://www.ibm.com/products/rhapsody)**  

  Established SysML/UML modeling environment strong in embedded systems, code generation, and integration with the IBM engineering lifecycle suite.



- **[Capella Cloud / Team for Capella](https://www.eclipse.org/capella/)**  

  Collaborative and cloud-oriented offerings around the open-source Capella MBSE workbench and Arcadia method.



- **[Valispace](https://www.valispace.com/)**  

  Web-based systems engineering platform focused on requirements, parameters, and data-driven collaboration for hardware and complex products.



- **[Vitech GENESYS](https://www.vitechcorp.com/)**  

  Model-based systems engineering environment supporting architecture, requirements, and behavior modeling with a long heritage in defense and complex systems.



- **[Sparx Enterprise Architect](https://sparxsystems.com/)**  

  Versatile modeling platform supporting SysML, UML, and many other notations; popular for architecture and systems modeling at various scales.



- **[Ansys ModelCenter](https://www.ansys.com/)**  

  Model-based engineering environment for integrating simulation, optimization, and multi-disciplinary analysis in a systems context.



- **[PTC Modeler (formerly Integrity Modeler)](https://www.ptc.com/)**  

  SysML/UML modeling tool integrated with PTC’s product and application lifecycle management offerings.



- **[Innoslate](https://www.innoslate.com/)**  

  Web-based MBSE and requirements management platform supporting modeling, simulation, and lifecycle collaboration.



- **[GENESYS / related Vitech offerings](https://www.vitechcorp.com/)**  

  Comprehensive MBSE toolset emphasizing system architecture and the connection between requirements, behavior, and physical design.



## Open-Source GitHub Projects

- **[Eclipse Capella](https://github.com/eclipse-capella/capella)**  

  The leading open-source MBSE workbench implementing the Arcadia method—used in industry for architecture modeling of complex systems (systems, software, hardware).



- **[Eclipse Papyrus](https://github.com/eclipse-papyrus/papyrus)**  

  Open-source UML/SysML modeling environment built on Eclipse; highly extensible for domain-specific languages and systems modeling.



- **[py-capellambse](https://github.com/dbinfrago/py-capellambse)**  

  Python library providing headless access to Capella models—enabling automation, analysis, document generation, and CI/CD integration without the Capella GUI.



- **[Capella Docker images & collaboration tooling](https://github.com/dbinfrago/capella-dockerimages)**  

  Containerized Capella, Papyrus, and related MBSE tools for reproducible environments and remote/collaborative setups.



- **[Arcadia / Capella add-ons and viewpoints](https://github.com/)**  

  Community and industrial extensions that add viewpoints, validation rules, and domain-specific modeling capabilities to Capella.



- **[SysML v2 pilot implementations and open libraries](https://github.com/)**  

  Emerging open efforts around the SysML v2 standard (textual and API-oriented) for next-generation systems modeling.



- **[Modelica and open multi-physics modeling tools](https://github.com/)**  

  Open modeling languages and tools often used alongside MBSE for physical/behavioral simulation of systems.



- **[Requirements and traceability open frameworks](https://github.com/)**  

  Open tools for managing requirements and linking them to models (complementary to full MBSE suites).



- **[Eclipse Modeling Framework (EMF) ecosystem](https://github.com/eclipse-emf)**  

  Foundational open modeling technologies underlying many SysML/UML tools including Papyrus and Capella.



- **[Open digital-thread and interchange prototypes](https://github.com/)**  

  Experimental projects exploring model interchange, federation, and open digital-thread patterns between MBSE tools.



### Additional Strong Open-Source Options

- Adopting **Capella + Arcadia** as the primary open industrial-grade MBSE solution for architecture definition.

- Using **Papyrus** when deep UML/SysML customization or Eclipse-based tooling is required.

- Automating model analysis and reporting with **py-capellambse** and related Python tooling.

- Combining open MBSE models with open simulation (Modelica, etc.) for analysis.

- Accepting that advanced collaborative features, proprietary SysML profiles, simulation integration, and enterprise support still favor commercial tools (Cameo, Rhapsody, Valispace, GENESYS, Enterprise Architect, etc.).

- Focusing open-source efforts on method adherence (Arcadia), model automation, and avoiding vendor lock-in for core architecture models.



**Frameworks for building custom systems**: Model architecture in Capella (Arcadia) → automate extraction and validation with Python (capellambse) → generate documents/interfaces → link to requirements and simulation tools → optionally synchronize selected views with commercial platforms. Suitable for organizations seeking open, method-driven MBSE. Many aerospace, defense, and complex-product teams continue to standardize on commercial MBSE suites for full lifecycle integration.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- MBSE models often represent safety-critical or export-controlled systems. Tool selection, model quality, and configuration management have engineering and compliance implications. Open-source tools require appropriate process controls. This list is not engineering or regulatory advice.



---

**Made for systems engineers, architects, and MBSE practitioners building complex products.**

Let's keep systems models rigorous, traceable, and as open as practical.
