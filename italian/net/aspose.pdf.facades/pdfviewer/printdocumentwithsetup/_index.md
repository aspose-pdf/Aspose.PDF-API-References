---
title: "PdfViewer.PrintDocumentWithSetup"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfViewer. Stampa il documento Pdf con una finestra di configurazione. Scegli una stampante usando la finestra di dialogo."
type: docs
weight: 340
url: /it/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## PdfViewer.PrintDocumentWithSetup method

Stampa il documento Pdf con una finestra di configurazione. Scegli una stampante usando la finestra.

```csharp
public void PrintDocumentWithSetup()
```

## Esempi

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.BindPdf(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog = false;   //do not produce the page number dialog when printing
iewer.PrintDocumentWithSetup();
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.BindPdf(@"d:\test.pdf")
iewer.AutoResize = True          'print the file with adjusted size
iewer.AutoRotate = True          'print the file with adjusted rotation
iewer.PrintPageDialog = False    'do not produce the page number dialog when printing
iewer.PrintDocumentWithSetup()
iewer.Close()
```

### Vedi anche

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


