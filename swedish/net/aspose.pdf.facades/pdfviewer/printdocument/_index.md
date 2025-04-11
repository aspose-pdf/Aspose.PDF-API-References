---
title: PdfViewer.PrintDocument
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer-metod. Skriver ut Pdf-dokumentet med standard skrivare
type: docs
weight: 320
url: /sv/net/aspose.pdf.facades/pdfviewer/printdocument/
---
## PdfViewer.PrintDocument metod

Skriver ut Pdf-dokumentet med standard skrivare.

```csharp
public void PrintDocument()
```

## Exempel

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

### Se Även

* klass [PdfViewer](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)