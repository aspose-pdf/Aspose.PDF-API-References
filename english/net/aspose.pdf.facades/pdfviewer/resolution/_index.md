---
title: "PdfViewer.Resolution"
linktitle: "Resolution"
articleTitle: "Resolution"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfViewer property. Gets or sets resolution during viewing and printing. The higher resolution, the slower speed. The default value is 150."
type: docs
weight: 530
url: "/net/aspose.pdf.facades/pdfviewer/resolution/"
product_version: "26.9.0"
---
## PdfViewer.Resolution property

Gets or sets resolution during viewing and printing. The higher resolution, the slower speed. The default value is 150.

This property changes the image resolution in page-to-image conversion flows: when the `PrintAsImage` is set
 to , or when `DecodePage` or `DecodeAllPages` method is called.
 To set a printer resolution for direct printing to a printer, use the `PrinterResolution` property
 in the [`PageSettings`](../../../aspose.pdf.printing/pagesettings/) class.

```csharp
public int Resolution { get; set; }
```

### Property Value

int

### See Also

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

