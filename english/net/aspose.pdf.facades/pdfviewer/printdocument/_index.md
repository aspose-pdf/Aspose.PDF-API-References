---
title: "PdfViewer.PrintDocument"
linktitle: "PrintDocument"
articleTitle: "PrintDocument"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfViewer method. Prints the Pdf document using default printer."
type: docs
weight: 230
url: "/net/aspose.pdf.facades/pdfviewer/printdocument/"
product_version: "26.9.0"
---
## PdfViewer.PrintDocument method

Prints the Pdf document using default printer.

```csharp
public void PrintDocument()
```

## Examples

```csharp
[C#]
 PdfViewer viewer = new PdfViewer();
 viewer.OpenPdfFile(@"d:\test.pdf");
 viewer.AutoResize = true; //print the file with adjusted size
 viewer.AutoRotate = true; //print the file with adjusted rotation
 viewer.PrintPageDialog=false;//do not produce the page number dialog when printing
 viewer.PrintDocument(ps);
 viewer.ClosePdfFile();
 
 [VisualBasic]
 Dim viewer As PdfViewer = new PdfViewer()
 viewer.OpenPdfFile(@"d:\test.pdf")
 viewer.AutoResize = true; 'print the file with adjusted size
 viewer.AutoRotate = true; 'print the file with adjusted rotation
 viewer.PrintPageDialog=false;//do not produce the page number dialog when printing
 viewer.PrintDocument(ps);
 viewer.ClosePdfFile()
```

### See Also

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

