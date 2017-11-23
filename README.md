CSXTransformation
========================

Utilities for validating and transforming [CiteSeerX document metadata](http://csxstatic.ist.psu.edu/about/data) in XML format.

* **Version:** 2013-06-24
* **Author:** Todd Shore
* **Website:**  https://github.com/errantlinguist/CSXTransformation
* **Licensing:** Copyright &copy; 2013&ndash;2014 Todd Shore. Licensed for distribution under the Apache License 2.0: See the files `NOTICE` and `LICENSE`.

Notes
--------------------------------------------------------------------------------
* The definitions provided by the XSD files in this project are permissive in that they validate CSX document data as "correct" even if certain elements are missing.
* The definitions provided by the XSD files in this project define a format superset of the actual schema seen in the CSX corpus, e.g. certain document elements are defined by the XSD as `nillable` elements even though the actual data from CSX never contains "nill" elements (in the corpus, the element of often left empty instead)
* `xsl:include` declarations in the code must be adjusted to point to valid URLs.
