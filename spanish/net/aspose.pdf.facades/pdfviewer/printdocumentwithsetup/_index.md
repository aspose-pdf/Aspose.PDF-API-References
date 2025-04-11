---
title: PdfViewer.PrintDocumentWithSetup
second_title: Aspose.PDF for .NET API Reference
description: Método PdfViewer. Imprime el documento Pdf con un cuadro de diálogo de configuración. Elija una impresora usando el cuadro de diálogo
type: docs
weight: 340
url: /es/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## Método PdfViewer.PrintDocumentWithSetup

Imprime el documento Pdf con un cuadro de diálogo de configuración. Elija una impresora usando el cuadro de diálogo.

```csharp
public void PrintDocumentWithSetup()
```

## Ejemplos

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

### Véase también

* clase [PdfViewer](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)