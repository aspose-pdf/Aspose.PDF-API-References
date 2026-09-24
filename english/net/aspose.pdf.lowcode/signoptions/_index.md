---
title: "SignOptions Class"
linktitle: "SignOptions"
articleTitle: "SignOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.SignOptions class. Represents Sign Options for plugin."
type: docs
weight: 840
url: "/net/aspose.pdf.lowcode/signoptions/"
keywords: "SignOptions, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SignOptions class

Represents Sign Options for [`Signature`](../../aspose.pdf.lowcode/signature/) plugin.

```csharp
public sealed class SignOptions : OrganizerBaseOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SignOptions](./signoptions/#constructor)(*string, string*) | Initializes new instance of the [`SignOptions`](../../aspose.pdf.lowcode/signoptions/) object with default options. |
| [SignOptions](./signoptions/#constructor_1)(*Stream, string*) | Initializes new instance of the [`SignOptions`](../../aspose.pdf.lowcode/signoptions/) object with default options. |

## Properties

| Name | Description |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.lowcode/organizerbaseoptions/closeinputstreams/) { get; set; } | Close input streams after operation completed. *(Inherited from OrganizerBaseOptions)* |
| [CloseOutputStreams](../../aspose.pdf.lowcode/organizerbaseoptions/closeoutputstreams/) { get; set; } | Close output streams after operation completed. *(Inherited from OrganizerBaseOptions)* |
| [Contact](./contact/) { get; set; } | The contact of signature. |
| [Inputs](../../aspose.pdf.lowcode/organizerbaseoptions/inputs/) { get; } | Returns OrganizerOptions plugin data collection. *(Inherited from OrganizerBaseOptions)* |
| [Location](./location/) { get; set; } | The location of signature. |
| [Name](./name/) { get; set; } | The name of existing signature field. |
| [Outputs](../../aspose.pdf.lowcode/organizerbaseoptions/outputs/) { get; } | Gets collection of added targets for saving operation results. *(Inherited from OrganizerBaseOptions)* |
| [PageNumber](./pagenumber/) { get; set; } | The page number on which signature is made. |
| [Reason](./reason/) { get; set; } | The reason of signature. |
| [Rectangle](./rectangle/) { get; set; } | The rect of signature. |
| [Visible](./visible/) { get; set; } | The visiblity of signature. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.lowcode/organizerbaseoptions/addinput/)(*IDataSource*) | Adds new data source to the PdfOrganizer plugin data collection. *(Inherited from OrganizerBaseOptions)* |
| [AddOutput](../../aspose.pdf.lowcode/organizerbaseoptions/addoutput/)(*IDataSource*) | Adds new data source to the PdfOrganizer plugin data collection. *(Inherited from OrganizerBaseOptions)* |

### See Also

* class [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

