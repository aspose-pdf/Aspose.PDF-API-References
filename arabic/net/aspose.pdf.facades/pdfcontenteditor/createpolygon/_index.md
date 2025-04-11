---
title: PdfContentEditor.CreatePolygon
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ تعليق مضلع
type: docs
weight: 230
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createpolygon/
---
## طريقة PdfContentEditor.CreatePolygon

تنشئ تعليق مضلع.

```csharp
public void CreatePolygon(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
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