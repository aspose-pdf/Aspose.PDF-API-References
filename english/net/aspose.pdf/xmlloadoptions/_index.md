---
title: "XmlLoadOptions Class"
linktitle: "XmlLoadOptions"
articleTitle: "XmlLoadOptions"
second_title: "Aspose.PDF for .NET"
description: "Represents options for loading/importing XML file into pdf document."
type: docs
weight: 3240
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
| [XmlLoadOptions](./xmlloadoptions/#constructor) | Creates [`XmlLoadOptions`](../../aspose.pdf/xmlloadoptions/) object without xsl data. |
| [XmlLoadOptions](./xmlloadoptions/#constructor_1)(*string*) | Creates [`XmlLoadOptions`](../../aspose.pdf/xmlloadoptions/) object with xsl data. |
| [XmlLoadOptions](./xmlloadoptions/#constructor_2)(*Stream*) | Creates [`XmlLoadOptions`](../../aspose.pdf/xmlloadoptions/) object with xsl data. |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. *(Inherited from LoadOptions)* |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../../aspose.pdf/loadoptions/) describes. *(Inherited from LoadOptions)* |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. *(Inherited from LoadOptions)* |
| [XslStream](./xslstream/) { get; } | Gets xsl data for converting xml into pdf document. |

## Methods

| Name | Description |
| --- | --- |
| [Finalize](./finalize/) |  |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

