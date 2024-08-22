---
title: PdfViewer.Resolution
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer property. Gets or sets resolution during viewing and printing. The higher resolution the slower speed. The default value is 150
type: docs
weight: 160
url: /net/aspose.pdf.facades/pdfviewer/resolution/
---
## PdfViewer.Resolution property

Gets or sets resolution during viewing and printing. The higher resolution, the slower speed. The default value is 150.

```csharp
public int Resolution { get; set; }
```

## Remarks

This property changes the image resolution in page-to-image conversion flows: when the [`PrintAsImage`](../printasimage/) is set to `true`, or when [`DecodePage`](../decodepage/) or [`DecodeAllPages`](../decodeallpages/) method is called. To set a printer resolution for direct printing to a printer, use the [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) property in the [`PageSettings`](../../../aspose.pdf.printing/pagesettings/) class.

### See Also

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


