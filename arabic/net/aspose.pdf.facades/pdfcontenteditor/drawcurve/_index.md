---
title: "PdfContentEditor.DrawCurve"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تنشئ تعليق توضيحي منحني"
type: docs
weight: 360
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## PdfContentEditor.DrawCurve method

ينشئ تعليقا من نوع المنحنى.

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
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
newApiEditor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100 };  //x1, y1, x2, y2, .. xn, yn
lineInfo.Visibility = true;
editor.DrawCurve(lineInfo, 1, new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [LineInfo](../../lineinfo/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


