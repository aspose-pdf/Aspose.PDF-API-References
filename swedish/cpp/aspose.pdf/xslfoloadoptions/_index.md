---
title: "Aspose::Pdf::XslFoLoadOptions-klass"
linktitle: "XslFoLoadOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::XslFoLoadOptions-klass. Representerar alternativ för att ladda/importera XSL-FO-fil till pdf-dokument i C++."
type: docs
weight: 21200
url: /sv/cpp/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class


Representerar alternativ för att läsa in/importera XSL-FO-fil till pdf-dokument.

```cpp
class XslFoLoadOptions : public Aspose::Pdf::XmlLoadOptions
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [ParsingErrorsHandlingTypes](./parsingerrorshandlingtypes/) | Källdokumentet XSLFO kan innehålla formateringsfel. Denna enum listar möjliga strategier för hantering av sådana formateringsfel. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_BasePath](./get_basepath/)() const | Basvägen/URL:en därifrån relativa sökvägar till externa resurser (om några) som refereras i den inlästa SVG-filen söks. |
| [get_XsltArgumentList](./get_xsltargumentlist/)() const | XsltArgumentList för att infoga värden i befintliga xls-parametrar. |
| [set_BasePath](./set_basepath/)(const System::String\&) | Basvägen/URL:en därifrån relativa sökvägar till externa resurser (om några) som refereras i den inlästa SVG-filen söks. |
| [set_XsltArgumentList](./set_xsltargumentlist/)(const System::SharedPtr\<System::Xml::Xsl::XsltArgumentList\>\&) | XsltArgumentList för att infoga värden i befintliga xls-parametrar. |
| [XslFoLoadOptions](./xslfoloadoptions/)() | Skapar ett [XslFoLoadOptions](./)-objekt utan xsl-data. |
| [XslFoLoadOptions](./xslfoloadoptions/)(const System::String\&) | Skapar [XslFoLoadOptions](./) objekt med xsl-data. |
| [XslFoLoadOptions](./xslfoloadoptions/)(const System::SharedPtr\<System::IO::Stream\>\&) | Skapar [XslFoLoadOptions](./) objekt med xsl-data. |
## Se även

* Class [XmlLoadOptions](../xmlloadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
