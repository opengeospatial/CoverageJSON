# Standard template

## Content

This folder contains the text for the standard

* document.adoc - the main standard document with references to all sections
* remaining adocs - each section of the standard document is in a separate document: follow directions in each document to populate
* figures - figures go here
* images - Image files for graphics go here. Image files for figures go in the "figures" directory. Only place in here images not used in figures (e.g., as parts of tables, as logos, etc.)
* requirements - directory for requirements and requirement classes to be referenced in the document
* code - sample code to accompany the standard, if desired
* abstract_tests - the Abstract Test Suite comprising one test for every requirement, optional
* UML - UML diagrams, if applicable

## Authoring

Refer to the Metanorma Authoring Guide for information about using metanorma https://www.metanorma.org/author/ogc/authoring-guide/

## Building

To produce the HTML and PDF of the document run `docker run -v "$(pwd)":/metanorma -v ${HOME}/.fontist/fonts/:/config/fonts metanorma/mn metanorma compile --agree-to-terms -t ogc -x xml,html,doc,pdf document.adoc`.
