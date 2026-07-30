---
title: "PdfViewer.PrintDocument"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfViewer. Imprime le document Pdf en utilisant l'imprimante par défaut"
type: docs
weight: 320
url: /fr/net/aspose.pdf.facades/pdfviewer/printdocument/
---
## PdfViewer.PrintDocument method

Imprime le document Pdf en utilisant l'imprimante par défaut.

```csharp
public void PrintDocument()
```

## Exemples

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

### Voir aussi

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


