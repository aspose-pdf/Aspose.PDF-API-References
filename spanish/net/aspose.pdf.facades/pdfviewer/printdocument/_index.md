---
title: PdfViewer.PrintDocument
second_title: Aspose.PDF for .NET API Reference
description: Método PdfViewer. Imprime el documento Pdf utilizando la impresora predeterminada
type: docs
weight: 320
url: /es/net/aspose.pdf.facades/pdfviewer/printdocument/
---
## Método PdfViewer.PrintDocument

Imprime el documento Pdf utilizando la impresora predeterminada.

```csharp
public void PrintDocument()
```

## Ejemplos

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

### Ver También

* clase [PdfViewer](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)