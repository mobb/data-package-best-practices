# Conventions and Definitions


## Audience

This document is intended for data managers. It assumes that readers are familiar with

- the basic structure of an XML document, and the ability to edit in an XML
  editor like OxygenXML or XMLSpy.
- the process for contributing data to a repository. If you reached this
  document from a repository's help-page, contact them for more information.

## Fonts and typeface

Numbered examples of EML nodes are in fixed-width font:

```xml
<?xml version="1.0" encoding="UTF-8"?>
```

XML element and attribute names, XPath and references to element names
in text are in bold face. Single element names are surrounded by angle
brackets, as they appear in XML.

<**dataTable**>  
**/eml:eml/\@packageId**

Some recommendations have special context, e.g., an XML element or
attribute may be requested by a community (e.g., LTER), or required by
the EDI repository (but not by other repositories).

_Context notes: Recommendations for EML usage in a specific context are
called "context notes", and are placed in separate paragraphs, in
italic._

## Definitions

<dl>
  <dt>EML preparer</dt>
  <dd>the person responsible for "building" the EML metadata
record. Generally, this is a data manager working with a project or
physical site that produces data.</dd>

  <dt>Contributor</dt>
  <dd>the research project contributing the data package, e.g.,
an LTER or OBFS site, or a Macrosystems project. Generally, the "EML
preparer" works with or for the "Contributor."</dd>

  <dt>Data package</dt>
  <dd>the EML metadata together with its entity or entities.
This is generally the unit housed in repositories. We use this term to
avoid confusion with the EML element "<b>dataset</b>".</dd>
</dl>

## Other EML Resources

Some sections refer to further information or tools. These can be found
on the EDI website, under "Resources and How To...", at
[https://environmentaldatarepository.org](https://environmentaldatarepository.org)

