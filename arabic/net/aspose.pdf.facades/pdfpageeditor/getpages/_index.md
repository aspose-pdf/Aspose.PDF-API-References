---
title: PdfPageEditor.GetPages
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfPageEditor. تعيد العدد الإجمالي للصفحات
type: docs
weight: 150
url: /ar/net/aspose.pdf.facades/pdfpageeditor/getpages/
---
## طريقة PdfPageEditor.GetPages

تعيد العدد الإجمالي للصفحات.

```csharp
public int GetPages()
```

### قيمة الإرجاع

عدد الصفحات.

## أمثلة

المثال التالي يوضح استخدام طريقة GetPages():

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
Console.WriteLine("Document has: " + editor.GetPages());
```

### انظر أيضًا

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)