# W3C Linked Data

## Principles

* Use URIs as names for everything
  * for abstract concepts
  * for specific instances of things in the universe
  * for identifiers of things in the universe
* Use HTTP URIs so that people and machines can lookup those names
  * Use HTTP content negotiation for determining data formats
  * Provide data in different data formats
    * html+rdfa
    * rdf-turtle
    * rdf-jsonld
    * rdf-xml
    * owl-turtle
    * owl-jsonld
    * owl-xml
* Provide useful information using standards (W3C RDF, W3C SPARQL)
  * Use RDF as the universal data model for publishing structured data
  * Make all URIs in the RDF graph dereferencible
  * Avoid RDF constructs that cause problems in linked data context
    * RDF reification
    * RDF collections and containers
    * unnamed blank nodes
* Include links to other URIs so that they can discover
  * relationship links
  * identity links
  * vocabulary links

## Open Data

* Provide linked data using an open license