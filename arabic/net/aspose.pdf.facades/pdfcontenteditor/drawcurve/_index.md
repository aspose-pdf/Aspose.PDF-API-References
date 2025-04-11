---
title: PdfContentEditor.DrawCurve
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ تعليق منحني
type: docs
weight: 360
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## طريقة PdfContentEditor.DrawCurve

تنشئ تعليق منحني.

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lineInfo | LineInfo | مثيل من فئة LineInfo. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق. |
| annotRect | Rectangle | مستطيل التعليق الذي يحدد موقع التعليق على الصفحة. |
| annotContents | String | محتويات التعليق. |

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