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

---

```
+----------------------------+    +----------------------------+    +----------------------------+
|                            |    |                            |    |                            |
|                            |    |                            |    |                            |
|                            |    |                            |    |                            |
|         DOCUMENT           |    |            TEXT            |    |          EDITION           |
|                            |    |                            |    |                            |
|                            |    |                            |    |                            |
|                            |    |                            |    |                            |
+----------------------------+    +----------------------------+    +----------------------------+
```

---

<div style="font-size:xx-large;">

```
    Charters and records of an Argovian Abbey and Bailiwick, 14-18ᵗʰ c.

 Scientific communication of the enlightenment (letters, reviews, essays)

Pre-eminent medieval narrative work based on 16 manuscripts and 70 fragments

       Articles, photos, letters, photo stories of a 20ᵗʰ c. author

                     +----------------------------+    +----------------------------+    +----------------------------+
                     |····························|    |                            |    |                            |
                     |····························|    |                            |    |                            |
                     |····························|    |                            |    |                            |
                     |········· DOCUMENT ·········|    |            TEXT            |    |          EDITION           |
                     |····························|    |                            |    |                            |
                     |····························|    |                            |    |                            |
                     |····························|    |                            |    |                            |
                     +----------------------------+    +----------------------------+    +----------------------------+

                       Typescript of a 1970s novel

                   Travel diaries of the 17ᵗʰ and 18ᵗʰ c.

        Complete works of a Swiss novelist and educator of the 19ᵗʰ c.

         Complete works of a late modern scholar, explorer, polymath

     Acts of the council of Christian bishops convened in Ephesus in AD 431
```

</div>

<!-- here: Bern exmaples -->
<!-- variation in: period, register/genre, language, script, structure, materiality -->

---

<div style="font-size:x-large;">

```
                               TEXT is a (surprisingly?) loose concept:
                               ========================================

         Object of research /          What is the 'text'? What belongs to the if?
         corpus definition             And what is its pretext, epitext, paratext?

         Textual criticism             What did the 'real' text look like?
                                       Perhaps also: What should the text actually look like?

         Textual genesis               How did the text come to be? What variants are extant?

+----------------------------+    +----------------------------+    +----------------------------+
|                            |    |····························|    |                            |
|                            |    |····························|    |                            |
|                            |    |····························|    |                            |
|         DOCUMENT           |    |··········· TEXT ···········|    |          EDITION           |
|                            |    |····························|    |                            |
|                            |    |····························|    |                            |
|                            |    |····························|    |                            |
+----------------------------+    +----------------------------+    +----------------------------+

         Priority of the               All versions are equal vs hierarchy of variants
         processual dimension

         Communicative function        What is the message underlying the text?

         Authorship attribution        Who wrote the text?

         Author intention              What was intended by the author/s?

         Characteristics of text       Static (as fixated on a document)
                                       Fluid (tradition, genesis)
                                       Continuously malleable (in the digital)
                                       Manifest at varying granularity
```

</div>

---

## <!-- here: global questions -->

<div class="source">
<code>
DeRose, S.J., Durand, D.G., Mylonas, E. et al. What is text, really?. J. Comput. High. Educ. 1, 3–26 (1990).

DOI: [10.1007/BF02941632](https://doi.org/10.1007/BF02941632) (or access via [SharedIt](https://rdcu.be/ddhju))
</code>

</div>

<style>
.slide {
  background: url(2023/img/ohco.png) center;
  background-size: contain;
  background-repeat: no-repeat;
}
.source { filter: invert();
          position: absolute;
          bottom: -10px;
          font-size: x-large; }
          code { opacity: 0.8 }
</style>

---

<div class="source">
<code>
Peter Robinson, What text really is not, and why editors have to learn to swim, Literary and Linguistic Computing, Volume 24, Issue 1, April 2009, Pages 41–52.

DOI: [10.1093/llc/fqn030](https://doi.org/10.1093/llc/fqn030)
</code>

</div>

<style>
.slide {
  background: url(2023/img/robinson.png) center;
  background-size: contain;
  background-repeat: no-repeat;
}
.source { filter: invert();
          position: absolute;
          bottom: -10px;
          font-size: x-large; }
          code { opacity: 0.8 }
</style>

---

<div style="font-size:xx-large;">

```
                                                                     Complete scholarly edition

                                                                     Historical-critical edition

                                                                         editio princeps

                                                                      (Hyper) diplomatic edition

                                                                          Facsimile edition

                                                                        Parallel-text edition

+----------------------------+    +----------------------------+    +----------------------------+
|                            |    |                            |    |····························|
|                            |    |                            |    |····························|
|                            |    |                            |    |····························|
|         DOCUMENT           |    |            TEXT            |    |········  EDITION ··········|
|                            |    |                            |    |····························|
|                            |    |                            |    |····························|
|                            |    |                            |    |····························|
+----------------------------+    +----------------------------+    +----------------------------+

                                                                         Text genetic edition

                                                                         Data centered edition

                                                                         Multilingual edition



                                                            DSE - how to leverage the potential of the digital?

```

</div>
<!-- goal: derive text from textual witnesses -->

---

```
        +---------------+ +---------------+ +---------------+ +---------------+
         \               \ \               \ \               \ \               \
          \               \ \               \ \   Editorial   \ \               \
           \  Selection    \ \  Preparation  \ \    core       \ \  Publication  \
           /               / /               / /  business     / /               /
          /               / /               / /               / /               /
         /               / /               / /               / /               /
        +---------------+ +---------------+ +---------------+ +---------------+
```

---

<span data-tooltip="Text Encoding Initiative">T E I</span>

<!-- methods, methodology; data formats -->

<style>
[data-tooltip]:hover {
	position: relative;
}
[data-tooltip]:hover::before {
	all: initial;
	font-family: Arial, Helvetica, sans-serif;
	display: inline-block;
	border-radius: 5px;
	padding: 10px;
	background-color: #1a1a1a;
	content: attr(data-tooltip);
	color: #f9f9f9;
	position: absolute;
	top: 100%;
	width: 400px;
	left: 50%;
	transform: translate(-50%, 0);
	margin-top: 15px;
	text-align: center;
	font-size: xx-large;
}
</style>

---

```xml
<TEI xmlns="http://www.tei-c.org/ns/1.0">
  <teiHeader>
    {metdadata}
  </teiHeader>
  <body>
    {hierarchical representation of the text}
  </body>
</TEI>
```

<!-- goal: describe what is in the source, not the intended rendering of the output -->

<!--
   * Core delivery: encoding guidelines
   * "Standard" for digital research with and on texts
   * Targets the semantical description of texts, not the implementation of a graphical interface
   * Open source
   * Community based
   * Multilingual
   * Possible presentation forms / renderings: CD ROM, PDF, HTML, API, XML?
 -->

---

```xml

<TEI xmlns="http://www.tei-c.org/ns/1.0">
  <teiHeader>
    <fileDesc>
      <titleStmt>
        <title>Who's blessed?</title>
      </titleStmt>
    </fileDesc>
  </teiHeader>
  <text>
    <body>
      <p>
        <quote>
          Blessed are the <choice>
            <sic>cheesemakers</sic>
            <corr cert="high">peacemakers</corr>
            <corr cert="low">placemakers</corr>
          </choice>:
          for they shall be called the children of God.
        </quote>
      </p>
    </body>
  </text>
</TEI>
```

---

As of revision [f18deffba](https://github.com/TEIC/TEI/commit/f18deffba) (TEI P5 Version 4.6.0, 4th April 2023)

- 126 distinctly-named model classes

<details><summary>e.g. <code>model.choicePart</code></summary>

[![model.choicePart](2023/img/model-choice-part.png)](https://tei-c.org/release/doc/tei-p5-doc/en/html/ref-model.choicePart.html)

</details>

- 81 distinctly-named attribute classes

<details><summary>e.g. <code>att.global.responsibility</code></summary>

[![att.global.responsibilty](2023/img/att-global-responsibility.png)](https://tei-c.org/release/doc/tei-p5-doc/en/html/ref-att.global.responsibility.html)

</details>

- 585 elements

<details><summary>e.g. <code>choice</code></summary>

[![choice](2023/img/element-choice.png)](https://tei-c.org/release/doc/tei-p5-doc/en/html/ref-att.global.responsibility.html)

<details><summary>e.g. <code>model.choicePart</code></summary>

<style>
li {width: 900px;}
</style>

---

History of the TEI

```
1987 Begin of a standardisation effort (by ACH / ACL / ALLC)
│  13.11.1987: TEI PCP1 "CLOSING STATEMENT OF THE VASSAR PLANNING CONFERENCE"
│
└── 1990 ❰ P1 ❱
  │   07.1990: first public proposal "Guidelines for the Encoding and Interchange
  │            of Machine-Readable Texts" (Ed. M. Sperberg-McQueen, L. Burnard)
  │
  └── 1992 ❰ P2 ❱  Development (four Working Committees and various WGs)
    │
    └── 1994 and 1999 ❰ P3 ❱ "Guidelines for Electronic Text Encoding and Interchange"
      │                      439 elements, 1292 pages; considered achievement of the goals of 1987
      │
      └── 1999 / 2000 TEI Consortium (TEIC)
        │
        └── 2002 ❰ P4 ❱ 441 elements; SGML, XML (new); retaining backwards compatibility
          │             initial goal: to rectify mistakes; outcome: identification of new potentials
          │
          └── 2007 ❰ P5 ❱ reorganisation and revision; no (full) compatibility to P4
                          ongoing development, most recently 04.04.2023: TEI P5 4.6.0
```

---

```
<quote>
  Blessed are the <choice>
    <sic>cheesemakers</sic>
    <corr cert="high">peacemakers</corr>
    <corr cert="low">placemakers</corr>
  </choice>:
  for they shall be called the children of God.
</quote>
```

Processing model for `choice`

```
<elementSpec ident="choice" mode="change">
 <model predicate="sic and corr"
  behaviour="alternate">
  <param name="default" value="corr"/>
  <param name="alternate" value="sic"/>
 </model>
</elementSpec>
```

---

<style>
.slide {
  background: url(https://raw.githubusercontent.com/DominicWeber/CUSO_UNIL/main/ScholarlyEditions/teipb2.png) center;
  background-size: contain;
  background-repeat: no-repeat;
}
</style>

---

XML: promise of

- suitability for markup / mixed content
- universality
- longevity
- human readability
- machine processability
- versatility / transformability
- quality assurance
- extensibility / customisability

---

But also:

- (over) complexity
- verbosity
- stuck in time (depending on the perspective)

---

Beyond XML

- Multi-version documents (Desmond Schmidt)
- Text as a Graph (TAG)

---

Approaches

- (La)TeX
- in-browser transformation (XSLT 1.0, CSS, SaxonJS)
- pipeline-based
  - XML transformation (Apache Cocoon, Kiln, XSLWeb, XProc 3.0, XPath's `fn:transform()` invoking XSLT 3.0 transformations)
  - continuous integration (coupling version control with auto-building and deployment)
- native XML databases (eXist-db, BaseX)
- ODD-based (teiPublisher)

---

Architectures

- monolithic (often the case for eXist-db)
- modular, micro-service oriented
- static components (preservation optimised)

<!-- workflows (manual, automated), data models and formats, presentation methods, also mention Geovistory and DaSCH -->

---

Challenges

- prioritising data over (print-inspired) presentation
- combining manual and machine-assisted workflows
- implement technically generic systems that allow for a high degree of specialisation to meet requirements of editions

---

<small>

```
                                                                                                                     +------------------+
                                                                                                                     | generic archival |
                                                                                                                     | platform (DaSCH) |
                                                                                                                     +------------------+



                                                                                                                          +-----------+
                                                                                                                          |           |
                                                                                                                          |  API for  |
                                                                                                                          |  data     |     JSON
                                                                                                                          |           |     JSON-LD
                        +- - - - - - - -+                                                                                 |           |     TEI
                        |               |                  transcription                                                  +----+------+     RDF                    +----------+
                             manual                        +-----------+             scholarly commentary                      |                                   |          |
                        |               |                                            +------------------+                      |                                   | frontend |
                        +- - - - - - - -+                                                                                      +---------------------------->      |          |
                                                                                                                                                                   |          |
                                                                                                                                         +------------------>      |          |
image preparation                                                                                           XXXXXXXXXXXXXXX              |                         +----------+
+---------------+                                                                                           XXXXXXXXXXXXXXX              |
                                                                                  correction                XX           XX              |
       +                +- - - - - - - -+                                         +--------+                XX  TEI XML  XX              |
       |                |               |                                                                   XX           XX              |
       |                   automated                                                                        XXXXXXXXXXXXXXX              |
       |                |               |                   layout detection                                XXXXXXXXXXXXXXX       +------+------+
       |                +- - - - - - - -+                   region definition                                                     |             |
       |                                         OCR        +---------------+                                                     |   search    |
       |                                         +-+                                                                              |   engine/   |
       |                                                                                                                          |   index     |
       |                                                                                                                          |             |
       |                                         HTR                                                                              +-------------+
       |                                         +-+                         entity detection
       |                                                                     named entity recognition                                                 +-----------+
       |                                                                     +----------------------+             +----------------+                  |           |
       |                                                                                                          |                |                  |  IIIF     |
       |                                                                                                          |  data archive/ |                  |  server   |
       |                          +              version control (data)                                           |  repository    |                  |           |
       |                          |                                                                               |                |                  +-----------+
       |                          +--------------------------------------+-------------------------->             +----------------+
       |                                                                 |                                                                                 ^
       |                                                                 |                                                                                 |
       +---------------------------------------------------------------------------------------------------------------------------------------------------+
                                                                         |
                                                                         |
                                                                         |                 CI / CD
                                                                         |
                                                                         +------------------------------------------------>

```

</small>

<style>
small {font-size: 1.2rem;}
</style>
