---
title: "PdfContentEditor.CreateCustomActionLink"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تنشئ رابطًا إلى إجراءات مخصصة في مستند PDF"
type: docs
weight: 140
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor.CreateCustomActionLink method

ينشئ رابطًا لإجراءات مخصصة في مستند PDF.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| originalPage | Int32 | رقم الصفحة الأصلية التي سيُنشأ فيها المستطيل المرتبط بالارتباط. |
| color | Color | لون المستطيل للنقر النشط. |
| actionName | Enum[] | المصفوفة التي تحتوي على الإجراءات (أعضاء تعداد PredefinedAction) المقابلة لتنفيذ عناصر القائمة في عارض Acrobat. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


