## The State of Digital Scholarly Editions (at <img alt="UoB" src="https://www.unibe.ch/media/logo_unibern@2x.png" height="100px;"/>)

XI Seminar Spring 2023

May 31ˢᵗ 2023

Peter Dängeli, Sebastian Flick; 
Data Science Lab (DSL)
---

## Common forms of digital publication in the humanities

- ⓵ collections
- ⓶ network analysis
- ⓷ digital scholarly edition

---

## ⓵ Publishing digital collections with Omeka

One System to Publish them all.

---

- Wordpress-like experience tailored to the needs of scholars
- Functions are extendable via [Modules](https://omeka.org/s/modules) (Plugins)
- _extensive API_ makes it flexible
- emphasis on Linked Open Data and the semantic web

---

### Linked Open Web and Omeka

- **R**esource **D**escription **F**ramework allows definition of classes and properties in triplets
- Using RDF Schemes creates the possibility to connect multiple data repositories
- Omeka-S provides widely used metadata Schemes out of the box (FOAF, dublin core, ...)
- custom vocabularies possible
- API-responses are [JSON-LD-formatted](https://json-ld.org/)
- JSON-LD is also embedded in the frontend

---

### Examples

---

[Corona-Memory](https://omeka.unibe.ch/s/corona-memory/page/welcome)

- First Omeka-S Collection at the DH Bern
- Multilingual
- Crowd sourcing
- Custom Layout / Template

---

[Oral History Archiv](https://www.oral-history-archiv.ch/)

- Complete custom frontend which consumes the API
- [github-repo](https://github.com/DHBern/HistFalk-OralHistoryArchive)

<!--
​
* mention mapping to various metadata schemes, custom ontologies and vocabularies, crowd sourcing, countless modules (https://omeka.org/s/modules ; comparable to WP approach but targeted at scholarly projects)
​
* show some UoB examples
​
  -->

---

#### Vanilla Omeka-S

[Sieben Siegel](https://omeka.unibe.ch/s/sieben_siegel/page/Hochstift)

- Project of Students accompanying a course

[Postdigital Displays](https://omeka.unibe.ch/s/Postdigital_Displays/page/einleitung)

- Project of a PhD Student accompanying her dissertation
- repository of media used in the dissertation

---

### Downsides

- building ontop of outdated technologies
  - security issues
  - poor developer experience
- updating self-hosted installations is painful and costly
- administrative and user-control tools are missing: no clear separation between sites.

---

## ⓶ Compile and publish relational data with Nodegoat

- custom data model
- relational modes of analysis with spatial and chronological forms of contextualisation
- UoB instance: https://nodegoat.unibe.ch/
- get in touch with [Sebastian Borkowski](mailto:sebastian.borkowski@unibe.ch)
  ​
  <!-- very briefly as this is really Sebastian's area of expertise -->
  ​

---

## ⓷ Digital Scholarly Editions (DSE)

<!-- workflows (manual, automated), data models and formats, presentation methods, also mention Geovistory and DaSCH -->
