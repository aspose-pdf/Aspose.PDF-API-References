---
title: PdfViewer.PrintDocumentWithSetup
second_title: Aspose.PDF for .NET API Reference
description: Método PdfViewer. Imprime o documento Pdf com uma caixa de diálogo de configuração. Escolha uma impressora usando a caixa de diálogo
type: docs
weight: 340
url: /pt/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## Método PdfViewer.PrintDocumentWithSetup

Imprime o documento Pdf com uma caixa de diálogo de configuração. Escolha uma impressora usando a caixa de diálogo.

```csharp
public void PrintDocumentWithSetup()
```

## Exemplos

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

### Veja Também

* classe [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)