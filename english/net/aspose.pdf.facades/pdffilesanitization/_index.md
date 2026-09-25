---
title: "PdfFileSanitization Class"
linktitle: "PdfFileSanitization"
articleTitle: "PdfFileSanitization"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfFileSanitization class. Represents sanitization and recovery API. Use it if you can't create/open documents in any other way."
type: docs
weight: 430
url: "/net/aspose.pdf.facades/pdffilesanitization/"
keywords: "PdfFileSanitization, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfFileSanitization class

Represents sanitization and recovery API.
 Use it if you can't create/open documents in any other way.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileSanitization](./pdffilesanitization/#constructor) | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. *(Inherited from Facade)* |
| [Log](./log/) { get; } | After file has Saved you can check what was done with file. |
| [UseRebuildXrefAndTrailer](./userebuildxrefandtrailer/) { get; set; } | Allows to generate new xref and trailer for document. |
| [UseTrimBottom](./usetrimbottom/) { get; set; } | Allows to remove data after pdf data. |
| [UseTrimTop](./usetrimtop/) { get; set; } | Allows to remove data before pdf data. |

## Methods

| Name | Description |
| --- | --- |
| [BindPdf](./bindpdf/)(*string*) | Binds a Pdf file for Sanitize. |
| [BindPdf](./bindpdf/)(*Stream*) | Binds a Pdf stream for Sanitize. |
| [BindPdf](./bindpdf/)(*Document*) | Initializes the facade. |
| [Close](./close/) | Closes the facade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/) | Disposes the facade. *(Inherited from Facade)* |
| [RebuildXrefAndTrailer](./rebuildxrefandtrailer/) | Removes old xref with trailer and creates a new xref with trailer. |
| [Recover](./recover/) | Recovers document. |
| [Save](./save/)(*string*) | Saves the result PDF to file. |
| [Save](./save/)(*Stream*) | Saves the result PDF to stream. |
| [TrimBottom](./trimbottom/) | Removes data after last %%EOF. |
| [TrimTop](./trimtop/) | Removes data before %PDF. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

