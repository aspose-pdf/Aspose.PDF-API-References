---
title: Aspose::Pdf::XmlLoadOptions class
linktitle: XmlLoadOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XmlLoadOptions class. Represents options for loading/importing XML file into pdf document in C++.'
type: docs
weight: 16700
url: /cpp/aspose.pdf/xmlloadoptions/
---
## XmlLoadOptions class


Represents options for loading/importing XML file into pdf document.

```cpp
class XmlLoadOptions : public Aspose::Pdf::LoadOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_DisableFontLicenseVerifications](../loadoptions/get_disablefontlicenseverifications/)() const | Gets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [get_LoadFormat](../loadoptions/get_loadformat/)() const | Represents file format which [LoadOptions](../loadoptions/) describes. |
| [get_WarningHandler](../loadoptions/get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [get_XslStream](./get_xslstream/)() const | Gets xsl data for converting xml into pdf document. |
| [LoadOptions](../loadoptions/loadoptions/)() |  |
| [set_DisableFontLicenseVerifications](../loadoptions/set_disablefontlicenseverifications/)(bool) | Sets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [set_WarningHandler](../loadoptions/set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [XmlLoadOptions](./xmlloadoptions/)() | Creates [XmlLoadOptions](./) object without xsl data. |
| [XmlLoadOptions](./xmlloadoptions/)(System::String) | Creates [XmlLoadOptions](./) object with xsl data. |
| [XmlLoadOptions](./xmlloadoptions/)(System::SharedPtr\<System::IO::Stream\>) | Creates [XmlLoadOptions](./) object with xsl data. |
| virtual [~XmlLoadOptions](./~xmlloadoptions/)() |  |
## See Also

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
