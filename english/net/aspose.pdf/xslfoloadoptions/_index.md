---
title: "XslFoLoadOptions Class"
linktitle: "XslFoLoadOptions"
articleTitle: "XslFoLoadOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.XslFoLoadOptions class. Represents options for loading/importing XSL-FO file into pdf document."
type: docs
weight: 3380
url: "/net/aspose.pdf/xslfoloadoptions/"
keywords: "XslFoLoadOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## XslFoLoadOptions class

Represents options for loading/importing XSL-FO file into pdf document.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XslFoLoadOptions](./xslfoloadoptions/#constructor) | Creates [`XslFoLoadOptions`](../../aspose.pdf/xslfoloadoptions/) object without xsl data. |
| [XslFoLoadOptions](./xslfoloadoptions/#constructor_1)(*string*) | Creates [`XslFoLoadOptions`](../../aspose.pdf/xslfoloadoptions/) object with xsl data. |
| [XslFoLoadOptions](./xslfoloadoptions/#constructor_2)(*Stream*) | Creates [`XslFoLoadOptions`](../../aspose.pdf/xslfoloadoptions/) object with xsl data. |

## Properties

| Name | Description |
| --- | --- |
| [BasePath](./basepath/) { get; set; } | The base path/url from which are searched relative paths to external resources (if any) referenced in loaded SVG file. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. *(Inherited from LoadOptions)* |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../../aspose.pdf/loadoptions/) describes. *(Inherited from LoadOptions)* |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. *(Inherited from LoadOptions)* |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Gets xsl data for converting xml into pdf document. *(Inherited from XmlLoadOptions)* |
| [XsltArgumentList](./xsltargumentlist/) { get; set; } | XsltArgumentList for inserting values into existing xls parameters. |

## Fields

| Name | Description |
| --- | --- |
| [ParsingErrorsHandlingType](./parsingerrorshandlingtype/) | Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handking of that errors. |

### See Also

* class [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

