---
title: PrintDocument
second_title: Aspose.PDF per .NET API Reference
description: Stampa il documento Pdf utilizzando la stampante predefinita.
type: docs
weight: 290
url: /it/net/aspose.pdf.facades/pdfviewer/printdocument/
---
## PdfViewer.PrintDocument method

Stampa il documento Pdf utilizzando la stampante predefinita.

```csharp
public void PrintDocument()
```

### Esempi

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         stampa il file con la dimensione regolata
iewer.AutoRotate = true;         stampa il file con la dimensione regolata
iewer.PrintPageDialog=false;stampa il file con la dimensione regolata
iewer.PrintDocument(ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")
iewer.AutoResize = true;         '//stampa il file con le dimensioni modificate
iewer.AutoRotate = true;         '//stampa il file con la rotazione regolata
iewer.PrintPageDialog=false;stampa il file con la dimensione regolata
iewer.PrintDocument(ps);
iewer.ClosePdfFile()
```

### Guarda anche

* class [PdfViewer](../../pdfviewer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfviewer)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->