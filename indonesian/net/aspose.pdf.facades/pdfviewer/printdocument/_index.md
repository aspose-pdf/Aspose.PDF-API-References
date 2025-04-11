---
title: PdfViewer.PrintDocument
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfViewer. Mencetak dokumen Pdf menggunakan printer default
type: docs
weight: 320
url: /id/net/aspose.pdf.facades/pdfviewer/printdocument/
---
## Metode PdfViewer.PrintDocument

Mencetak dokumen Pdf menggunakan printer default.

```csharp
public void PrintDocument()
```

## Contoh

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

### Lihat Juga

* kelas [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)