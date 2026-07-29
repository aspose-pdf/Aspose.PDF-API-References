---
title: "PdfContentEditor.CreateCaret"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تنشئ تعليقة caret."
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor.CreateCaret method

ينشئ تعليقة caret.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | Int32 | عدد الصفحة الأصلية التي سيُنشأ فيها التعليق. |
| annotRect | Rectangle | مستطيل التعليق يحدد موقع التعليق على الصفحة. |
| caretRect | Rectangle | الحدود الفعلية للـ caret الأساسي. |
| رمز | String | سيتم ربط رمز بالـ caret. يمكن أن تكون القيمة: "P" (فقرة)، "None". |
| annotContents | String | محتوى التعليق التوضيحي. |
| color | Color | لون التعليق التوضيحي. |

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


