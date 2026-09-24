---
title: "PdfViewer.PrintDocumentWithSetup"
linktitle: "PrintDocumentWithSetup"
articleTitle: "PrintDocumentWithSetup"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfViewer method. Prints the Pdf document with a setup dialog. Choose a printer using the dialog."
type: docs
weight: 200
url: "/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/"
product_version: "26.9.0"
---
## PrintDocumentWithSetup() {#printdocumentwithsetup}

Prints the Pdf document with a setup dialog. Choose a printer using the dialog.

```csharp
public void PrintDocumentWithSetup()
```

## Examples

```csharp
[C#]
 PdfViewer viewer = new PdfViewer();
 viewer.BindPdf(@"d:\test.pdf");
 viewer.AutoResize = true; //print the file with adjusted size
 viewer.AutoRotate = true; //print the file with adjusted rotation
 viewer.PrintPageDialog = false; //do not produce the page number dialog when printing
 viewer.PrintDocumentWithSetup();
 viewer.Close();
 
 [VisualBasic]
 Dim viewer As New PdfViewer()
 viewer.BindPdf(@"d:\test.pdf")
 viewer.AutoResize = True 'print the file with adjusted size
 viewer.AutoRotate = True 'print the file with adjusted rotation
 viewer.PrintPageDialog = False 'do not produce the page number dialog when printing
 viewer.PrintDocumentWithSetup()
 viewer.Close()
```

### See Also

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

