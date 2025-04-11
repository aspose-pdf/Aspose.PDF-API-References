---
title: PdfViewer.PrintDocumentWithSetup
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer-Methode. Druckt das Pdf-Dokument mit einem Einstellungsdialog. Wählen Sie einen Drucker über den Dialog aus.
type: docs
weight: 340
url: /de/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## PdfViewer.PrintDocumentWithSetup-Methode

Druckt das Pdf-Dokument mit einem Einstellungsdialog. Wählen Sie einen Drucker über den Dialog aus.

```csharp
public void PrintDocumentWithSetup()
```

## Beispiele

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

### Siehe auch

* Klasse [PdfViewer](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)