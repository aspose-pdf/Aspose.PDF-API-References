---
title: PdfContentEditor.CreateCustomActionLink
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ رابطًا للإجراءات المخصصة في مستند PDF
type: docs
weight: 140
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## طريقة PdfContentEditor.CreateCustomActionLink

تنشئ رابطًا للإجراءات المخصصة في مستند PDF.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| originalPage | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء المستطيل المرتبط بالرابط. |
| color | Color | لون المستطيل للنقر النشط. |
| actionName | Enum[] | مصفوفة من الإجراءات (أعضاء من تعداد PredefinedAction) المقابلة لتنفيذ عناصر القائمة في عارض Acrobat. |

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