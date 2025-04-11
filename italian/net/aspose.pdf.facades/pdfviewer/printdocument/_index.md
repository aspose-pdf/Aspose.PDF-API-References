---
title: PdfViewer.PrintDocument
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfViewer. Stampa il documento Pdf utilizzando la stampante predefinita
type: docs
weight: 320
url: /it/net/aspose.pdf.facades/pdfviewer/printdocument/
---
## Metodo PdfViewer.PrintDocument

Stampa il documento Pdf utilizzando la stampante predefinita.

```csharp
public void PrintDocument()
```

## Esempi

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

### Vedi anche

* classe [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)