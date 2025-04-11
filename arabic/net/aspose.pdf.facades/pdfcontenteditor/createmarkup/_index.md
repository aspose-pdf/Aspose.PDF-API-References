---
title: PdfContentEditor.CreateMarkup
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ تعليق توضيحي في مستند PDF
type: docs
weight: 200
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## طريقة PdfContentEditor.CreateMarkup

تنشئ تعليق توضيحي في مستند PDF.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل الذي يحدد موقع التعليق على الصفحة. |
| contents | String | محتويات التعليق. |
| type | Int32 | نوع التعليق التوضيحي. يمكن أن يكون 0 (تسليط الضوء)، 1 (تسطير)، 2 (شطب)، 3 (متموج). |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق. |
| clr | Color | لون التعليق التوضيحي. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)