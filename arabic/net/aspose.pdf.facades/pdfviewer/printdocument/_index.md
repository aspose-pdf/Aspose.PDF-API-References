---
title: PrintDocument
second_title: Aspose.PDF لمرجع .NET API
description: طباعة مستند Pdf باستخدام الطابعة الافتراضية.
type: docs
weight: 290
url: /ar/net/aspose.pdf.facades/pdfviewer/printdocument/
---
## PdfViewer.PrintDocument method

طباعة مستند Pdf باستخدام الطابعة الافتراضية.

```csharp
public void PrintDocument()
```

### أمثلة

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         // طباعة الملف بالحجم المعدل
iewer.AutoRotate = true;         // طباعة الملف مع التدوير المعدل
iewer.PrintPageDialog=false;// لا تنتج مربع حوار رقم الصفحة عند الطباعة
iewer.PrintDocument(ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")
iewer.AutoResize = true;         'اطبع الملف بالحجم المعدل
iewer.AutoRotate = true;         'اطبع الملف مع التدوير المعدل
iewer.PrintPageDialog=false;// لا تنتج مربع حوار رقم الصفحة عند الطباعة
iewer.PrintDocument(ps);
iewer.ClosePdfFile()
```

### أنظر أيضا

* class [PdfViewer](../../pdfviewer)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfviewer)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
