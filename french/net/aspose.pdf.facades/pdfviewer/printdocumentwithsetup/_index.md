---
title: "PdfViewer.PrintDocumentWithSetup"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfViewer. Imprime le document Pdf avec une boîte de dialogue de configuration. Choisissez une imprimante à l'aide de la boîte de dialogue"
type: docs
weight: 340
url: /fr/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## PdfViewer.PrintDocumentWithSetup method

Imprime le document Pdf avec une boîte de dialogue de configuration. Choisissez une imprimante à l'aide de la boîte de dialogue.

```csharp
public void PrintDocumentWithSetup()
```

## Exemples

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

### Voir aussi

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


