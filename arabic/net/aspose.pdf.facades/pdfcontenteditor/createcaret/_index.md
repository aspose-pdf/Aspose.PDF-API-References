---
title: PdfContentEditor.CreateCaret
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ تعليق المؤشر
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## طريقة PdfContentEditor.CreateCaret

تنشئ تعليق المؤشر.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| الصفحة | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق. |
| annotRect | Rectangle | مستطيل التعليق الذي يحدد موقع التعليق على الصفحة. |
| caretRect | Rectangle | الحدود الفعلية للمؤشر الأساسي. |
| الرمز | String | سيتم ربط رمز بالمؤشر. القيمة يمكن أن تكون: "P" (فقرة)، "لا شيء". |
| محتويات التعليق | String | محتويات التعليق. |
| اللون | Color | لون التعليق. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCaret(1,
    new System.Drawing.Rectangle(50, 50, 100, 100),
    new System.Drawing.Rectangle(60, 60, 70, 70),
    "None", "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)