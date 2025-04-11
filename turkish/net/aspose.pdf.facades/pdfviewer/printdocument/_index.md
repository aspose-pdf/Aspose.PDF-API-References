---
title: PdfViewer.PrintDocument
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer metodu. Pdf belgesini varsayılan yazıcıyı kullanarak yazdırır
type: docs
weight: 320
url: /tr/net/aspose.pdf.facades/pdfviewer/printdocument/
---
## PdfViewer.PrintDocument metodu

Pdf belgesini varsayılan yazıcıyı kullanarak yazdırır.

```csharp
public void PrintDocument()
```

## Örnekler

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
iewer.PrintDocument(ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")
iewer.AutoResize = true;         'print the file with adjusted size
iewer.AutoRotate = true;         'print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
iewer.PrintDocument(ps);
iewer.ClosePdfFile()
```

### Ayrıca Bakınız

* sınıf [PdfViewer](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)