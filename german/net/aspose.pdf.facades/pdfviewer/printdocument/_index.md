---
title: PdfViewer.PrintDocument
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer-Methode. Druckt das Pdf-Dokument mit dem Standarddrucker
type: docs
weight: 320
url: /de/net/aspose.pdf.facades/pdfviewer/printdocument/
---
## PdfViewer.PrintDocument-Methode

Druckt das Pdf-Dokument mit dem Standarddrucker.

```csharp
public void PrintDocument()
```

## Beispiele

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

### Siehe auch

* Klasse [PdfViewer](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)