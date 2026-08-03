---
title: "PdfViewer.PrintDocumentWithSetup"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfViewer-metod. Skriver ut Pdf-dokumentet med en inställningsdialog. Välj en skrivare med hjälp av dialogen."
type: docs
weight: 340
url: /sv/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## PdfViewer.PrintDocumentWithSetup method

Skriver ut Pdf-dokumentet med en installationsdialog. Välj en skrivare via dialogen.

```csharp
public void PrintDocumentWithSetup()
```

## Exempel

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

### Se även

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


