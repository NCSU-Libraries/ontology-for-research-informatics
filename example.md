#Example

This document outlines how the ontology has been used to investigate research informatics offerings at a specific institution. 

##Properties

Along with **Definition** and **Definition Source**, each "thing" was given a **Libraries Page Reference** property.

**Definition** 
A brief definition or description of a thing.

**Definition Source**
The source of the Definition.

**Libraries Page Reference**
Libraries webpages where the thing was referenced. "Difficult to search for" was used for broad or generic things, file format things, or things with multiple meanings.



##Relationships

####hasFunction
A thing could only have one function. 

**Concept**

Examples include:

* Copyright
* Fair Use
* Open Access

**Activity**

Examples include:

* Data cleaning
* Text mining
* Visualization

**Tool**

Examples include:

* GIS
* JavaScript
* Regular expression

**Software**

Examples include:

* MALLET
* Tableau
* D3

**Source**

Examples include:

* Data set
* JSTOR
* Text corpus

####usedDuring
A thing could be used during one or more research activities. The Research Activities from the [TaDiRAH](https://github.com/dhtaxonomy/TaDiRAH) taxonomy as described [here](https://github.com/dhtaxonomy/TaDiRAH/blob/master/reading/activities.md) were used.


**Capture**

Examples include:

* Transcription
* Copyright
* API


**Creation**

Examples include:

* Object-oriented programming
* Writing
* Intellectual property

**Enrichment**

Examples include:

* Georeferencing
* Descriptive metadata
* OpenRefine


**Analysis and Interpretation**

Examples include:

* Data mining
* Visualization
* MALLET

**Storage**

Examples include:

* Machine-readable
* Digital repository
* PDF


**Dissemination**

Examples include:

* Scholarly communication
* Open access
* Drupal




####foundIn
The "bins" found on the Libraries' [Research Support Portal](http://www.lib.ncsu.edu/services/research-support) were used to describe where a thing was found on the Libraries' website.
A thing could be found in multiple bins, on *Other Pages* and/or in *Books and/or Journals*. 

Care was taken that a thing was not tagged as being in one bin when in actuality that bin was linking to another bin. 


* [**Collections**](http://www.lib.ncsu.edu/do/collections)

* [**Citation Management**](https://www.lib.ncsu.edu/do/reference-management)

* [**Data and GIS**](https://www.lib.ncsu.edu/data)

* [**Grants and Funding**](http://www.lib.ncsu.edu/do/grantsandfunding)

* [**Data Management**](http://www.lib.ncsu.edu/data-management)

* [**Publishing and Copyright**](http://www.lib.ncsu.edu/cdsc)

* [**Visualization**](http://www.lib.ncsu.edu/do/visualization)

* [**Measuring Research Impact**](https://www.lib.ncsu.edu/measuring-research-impact)

* **Other Pages**
Used when a thing was found on pages in the lib.ncsu.edu domain, but those pages were not linked from the main Research Support Portal. 

* **Books and/or Journals**
Books and/or Journals was used when information about a thing was found in the Libraries' collections. This was most often used for things that weren't significantly represented elsewhere on the website. 

##Terms of Use

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a> by North Carolina State University.
