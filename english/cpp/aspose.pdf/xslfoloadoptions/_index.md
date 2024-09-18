---
title: Aspose::Pdf::XslFoLoadOptions class
linktitle: XslFoLoadOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XslFoLoadOptions class. Represents options for loading/importing XSL-FO file into pdf document in C++.'
type: docs
weight: 17900
url: /cpp/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class


Represents options for loading/importing XSL-FO file into pdf document.

```cpp
class XslFoLoadOptions : public Aspose::Pdf::XmlLoadOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_BasePath](./get_basepath/)() const | The base path/url from which are searched relative paths to external resources (if any) referenced in loaded SVG file. |
| [get_DisableFontLicenseVerifications](../loadoptions/get_disablefontlicenseverifications/)() const | Gets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [get_LoadFormat](../loadoptions/get_loadformat/)() const | Represents file format which [LoadOptions](../loadoptions/) describes. |
| [get_WarningHandler](../loadoptions/get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [get_XslStream](../xmlloadoptions/get_xslstream/)() const | Gets xsl data for converting xml into pdf document. |
| [get_XsltArgumentList](./get_xsltargumentlist/)() const | XsltArgumentList for inserting values into existing xls parameters. |
| [LoadOptions](../loadoptions/loadoptions/)() |  |
| [set_BasePath](./set_basepath/)(System::String) | The base path/url from which are searched relative paths to external resources (if any) referenced in loaded SVG file. |
| [set_DisableFontLicenseVerifications](../loadoptions/set_disablefontlicenseverifications/)(bool) | Sets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [set_WarningHandler](../loadoptions/set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [set_XsltArgumentList](./set_xsltargumentlist/)(System::SharedPtr\<System::Xml::Xsl::XsltArgumentList\>) | XsltArgumentList for inserting values into existing xls parameters. |
| [XmlLoadOptions](../xmlloadoptions/xmlloadoptions/)() | Creates [XmlLoadOptions](../xmlloadoptions/) object without xsl data. |
| [XmlLoadOptions](../xmlloadoptions/xmlloadoptions/)(System::String) | Creates [XmlLoadOptions](../xmlloadoptions/) object with xsl data. |
| [XmlLoadOptions](../xmlloadoptions/xmlloadoptions/)(System::SharedPtr\<System::IO::Stream\>) | Creates [XmlLoadOptions](../xmlloadoptions/) object with xsl data. |
| [XslFoLoadOptions](./xslfoloadoptions/)() | Creates [XslFoLoadOptions](./) object without xsl data. |
| [XslFoLoadOptions](./xslfoloadoptions/)(System::String) | Creates [XslFoLoadOptions](./) object with xsl data. |
| [XslFoLoadOptions](./xslfoloadoptions/)(System::SharedPtr\<System::IO::Stream\>) | Creates [XslFoLoadOptions](./) object with xsl data. |
| virtual [~XmlLoadOptions](../xmlloadoptions/~xmlloadoptions/)() |  |
## See Also

* Class [XmlLoadOptions](../xmlloadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
