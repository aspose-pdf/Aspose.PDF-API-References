---
title: "PdfViewer.PrintDocumentWithSetup"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfViewer. تطبع مستند Pdf مع حوار الإعداد. اختر طابعة باستخدام الحوار."
type: docs
weight: 340
url: /ar/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## PdfViewer.PrintDocumentWithSetup method

يطبع مستند Pdf باستخدام حوار الإعداد. اختر طابعة باستخدام الحوار.

```csharp
public void PrintDocumentWithSetup()
```

## أمثلة

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

### انظر أيضًا

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


