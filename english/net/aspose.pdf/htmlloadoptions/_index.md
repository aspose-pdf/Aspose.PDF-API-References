---
title: "HtmlLoadOptions Class"
linktitle: "HtmlLoadOptions"
articleTitle: "HtmlLoadOptions"
second_title: "Aspose.PDF for .NET"
description: "Represents options for loading/importing html file into pdf document."
type: docs
weight: 1160
url: "/net/aspose.pdf/htmlloadoptions/"
keywords: "HtmlLoadOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## HtmlLoadOptions class

Represents options for loading/importing html file into pdf document.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlLoadOptions](./htmlloadoptions/#constructor) | Creates load options for converting html into pdf document with empty base path. |
| [HtmlLoadOptions](./htmlloadoptions/#constructor_1)(*string*) | Creates load options for converting html into pdf document with defined base path. |

## Properties

| Name | Description |
| --- | --- |
| [BasePath](./basepath/) { get; } | The base path/url for the html file. |
| [CreateLogicalStructure](./createlogicalstructure/) { get; set; } | Gets or sets a value indicating whether to create a logical structure in the resulting PDF document. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. *(Inherited from LoadOptions)* |
| [HtmlMediaType](./htmlmediatype/) { get; set; } | Gets or sets possible media types used during rendering. |
| [InputEncoding](./inputencoding/) { get; set; } | Gets or sets the attribute specifying the encoding used for this document at the time of the parsing. If this attribute is null the encoding will determine from document character set atribute. |
| [IsEmbedFonts](./isembedfonts/) { get; set; } | Gets or sets fonts embedding to result document. |
| [IsPriorityCssPageRule](./isprioritycsspagerule/) { get; set; } | Gets or sets the flag that specifies that @page rules defined in css will override values defined in PageInfo. |
| [IsRenderToSinglePage](./isrendertosinglepage/) { get; set; } | Gets or sets rendering all document to single page. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../../aspose.pdf/loadoptions/) describes. *(Inherited from LoadOptions)* |
| [PageInfo](./pageinfo/) { get; set; } | Gets or sets document page info. |
| [PageLayoutOption](./pagelayoutoption/) { get; set; } | Gets or sets layout option. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. *(Inherited from LoadOptions)* |

## Fields

| Name | Description |
| --- | --- |
| [CustomLoaderOfExternalResources](./customloaderofexternalresources/) | Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes). |
| [ExternalResourcesCredentials](./externalresourcescredentials/) | If loading of external data referenced in HTML. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

