---
title: "PdfContentEditor.CreatePolygon"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. ينشئ تعليق مضلع."
type: docs
weight: 230
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createpolygon/
---
## PdfContentEditor.CreatePolygon method

ينشئ تعليقة مضلع.

```csharp
public void CreatePolygon(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| lineInfo | LineInfo | مثال من فئة LineInfo. |
| صفحة | Int32 | عدد الصفحة الأصلية التي سيُنشأ فيها التعليق. |
| annotRect | Rectangle | مستطيل التعليق يحدد موقع التعليق على الصفحة. |
| annotContents | String | محتوى التعليق التوضيحي. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolygon(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [LineInfo](../../lineinfo/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


