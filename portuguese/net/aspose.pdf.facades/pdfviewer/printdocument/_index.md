---
title: PdfViewer.PrintDocument
second_title: Aspose.PDF for .NET API Reference
description: Método PdfViewer. Imprime o documento Pdf usando a impressora padrão
type: docs
weight: 320
url: /pt/net/aspose.pdf.facades/pdfviewer/printdocument/
---
## Método PdfViewer.PrintDocument

Imprime o documento Pdf usando a impressora padrão.

```csharp
public void PrintDocument()
```

## Exemplos

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

### Veja Também

* classe [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)