---
title: PrintDocumentWithSetup
second_title: Aspose.PDF per .NET API Reference
description: Stampa il documento Pdf con una finestra di configurazione. Scegli una stampante utilizzando la finestra di dialogo.
type: docs
weight: 310
url: /it/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## PdfViewer.PrintDocumentWithSetup method

Stampa il documento Pdf con una finestra di configurazione. Scegli una stampante utilizzando la finestra di dialogo.

```csharp
public void PrintDocumentWithSetup()
```

### Esempi

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         stampa il file con la dimensione regolata
iewer.AutoRotate = true;         stampa il file con la dimensione regolata
iewer.PrintPageDialog=false;stampa il file con la dimensione regolata
iewer.PrintDocumentWithSetup();
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")   
iewer.AutoResize = true          '//stampa il file con le dimensioni modificate
iewer.AutoRotate = true          '//stampa il file con la rotazione regolata
iewer.PrintPageDialog=false;stampa il file con la dimensione regolata
iewer.PrintDocumentWithSetup()
iewer.ClosePdfFile()
```

### Guarda anche

* class [PdfViewer](../../pdfviewer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfviewer)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->