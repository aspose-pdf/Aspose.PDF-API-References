---
title: PdfViewer.PrintDocumentWithSetup
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer method. Prints the Pdf document with a setup dialog. Choose a printer using the dialog
type: docs
weight: 340
url: /net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## PdfViewer.PrintDocumentWithSetup method

Prints the Pdf document with a setup dialog. Choose a printer using the dialog.

```csharp
public void PrintDocumentWithSetup()
```

## Examples

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

### See Also

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


