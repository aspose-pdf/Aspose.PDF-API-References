---
title: PdfViewer.PrintDocument
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfViewer. تطبع مستند Pdf باستخدام الطابعة الافتراضية
type: docs
weight: 320
url: /ar/net/aspose.pdf.facades/pdfviewer/printdocument/
---
## طريقة PdfViewer.PrintDocument

تطبع مستند Pdf باستخدام الطابعة الافتراضية.

```csharp
public void PrintDocument()
```

## أمثلة

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

### انظر أيضًا

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)