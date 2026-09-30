---
title: "XmlLoadOptions Class"
linktitle: "XmlLoadOptions"
articleTitle: "XmlLoadOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.XmlLoadOptions class. Represents options for loading/importing XML file into pdf document."
type: docs
weight: 3200
url: "/net/aspose.pdf/xmlloadoptions/"
keywords: "XmlLoadOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## XmlLoadOptions class

Represents options for loading/importing XML file into pdf document.

```csharp
public class XmlLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XmlLoadOptions](./xmlloadoptions/#constructor)() | Creates [`XmlLoadOptions`](../../aspose.pdf/xmlloadoptions/) object without xsl data. |
| [XmlLoadOptions](./xmlloadoptions/#constructor_1)(Stream) | Creates [`XmlLoadOptions`](../../aspose.pdf/xmlloadoptions/) object with xsl data. |
| [XmlLoadOptions](./xmlloadoptions/#constructor_2)(string) | Creates [`XmlLoadOptions`](../../aspose.pdf/xmlloadoptions/) object with xsl data. |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When , allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default . |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../../aspose.pdf/loadoptions/) describes. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [XslStream](./xslstream/) { get; } | Gets xsl data for converting xml into pdf document. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

