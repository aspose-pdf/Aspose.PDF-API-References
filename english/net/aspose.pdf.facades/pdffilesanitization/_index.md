---
title: "PdfFileSanitization Class"
linktitle: "PdfFileSanitization"
articleTitle: "PdfFileSanitization"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfFileSanitization class. Represents sanitization and recovery API. Use it if you can't create/open documents in any other way."
type: docs
weight: 420
url: "/net/aspose.pdf.facades/pdffilesanitization/"
keywords: "PdfFileSanitization, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
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
| [PdfFileSanitization](pdffilesanitization/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | After file has Saved you can check what was done with file. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | Allows to generate new xref and trailer for document. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | Allows to remove data after pdf data |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | Allows to remove data before pdf data. |

## Methods

| Name | Description |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(string) | Binds a Pdf file for Sanitize. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | Binds a Pdf stream for Sanitize. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(Document) | Initializes the facade. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | Closes the facade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | Removes old xref with trailer and creates a new xref with trailer. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | Recovers document. Use properties to customize. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(string) | Saves the result PDF to file. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(Stream) | Saves the result PDF to stream. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | Removes data after last %%EOF. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | Removes data before %PDF. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

