# ADES XML Schema

The [Astrometry Data Exchange Standard](http://www.minorplanetcenter.net/mpec/K15/K15O06.html) defines a number of data fields.  These are described in the XML schema file `ades.xsd`.  The standard also gives an example of how data elements might be organized in an XML document.  The file `example.xsd` shows an organization for all elements of `ades.xsd`.  The example XML data document from standard is reproduced here as `example.xml`.  Finally, a short Python script is included to demonstrate validation of `example.xml` against the schema.

### Status

Totally first draft encoding of a developing standard.  "Developing" means not accepted, not finalized.  "Totally first draft" means rudimentary, with very few features, and expected to have errors.

### Issues

The issue tracker is active on this repository.  Feel free to submit not only apparent errors and inconsistencies, but any questions or concerns.

### validate.py

Note this imports [lxml](http://lxml.de/).  On Linux anyway `pip install` worked fine for me.