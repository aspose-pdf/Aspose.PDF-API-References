---
title: Aspose::Pdf::XslFoLoadOptions class
linktitle: XslFoLoadOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XslFoLoadOptions class. Represents options for loading/importing XSL-FO file into pdf document in C++.'
type: docs
weight: 21200
url: /cpp/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class


Represents options for loading/importing XSL-FO file into pdf document.

```cpp
class XslFoLoadOptions : public Aspose::Pdf::XmlLoadOptions
```

## Enums

| Enum | Description |
| --- | --- |
| [ParsingErrorsHandlingTypes](./parsingerrorshandlingtypes/) | Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handling of such formatting errors. |
## Methods

| Method | Description |
| --- | --- |
| [get_BasePath](./get_basepath/)() const | The base path/url from which are searched relative paths to external resources (if any) referenced in loaded SVG file. |
| [get_XsltArgumentList](./get_xsltargumentlist/)() const | XsltArgumentList for inserting values into existing xls parameters. |
| [set_BasePath](./set_basepath/)(System::String) | The base path/url from which are searched relative paths to external resources (if any) referenced in loaded SVG file. |
| [set_XsltArgumentList](./set_xsltargumentlist/)(System::SharedPtr\<System::Xml::Xsl::XsltArgumentList\>) | XsltArgumentList for inserting values into existing xls parameters. |
| [XslFoLoadOptions](./xslfoloadoptions/)() | Creates [XslFoLoadOptions](./) object without xsl data. |
| [XslFoLoadOptions](./xslfoloadoptions/)(System::String) | Creates [XslFoLoadOptions](./) object with xsl data. |
| [XslFoLoadOptions](./xslfoloadoptions/)(System::SharedPtr\<System::IO::Stream\>) | Creates [XslFoLoadOptions](./) object with xsl data. |
## See Also

* Class [XmlLoadOptions](../xmlloadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
