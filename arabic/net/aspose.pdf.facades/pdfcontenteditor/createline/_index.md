---
title: "PdfContentEditor.CreateLine"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تنشئ تعليقا للخط"
type: docs
weight: 180
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine method

ينشئ تعليقة خط.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق يحدد موقع التعليق على الصفحة. |
| contents | String | محتوى التعليق التوضيحي. |
| x1 | Single | الإحداثي الأفقي الابتدائي للخط. |
| y1 | Single | الإحداثي الرأسي الابتدائي للخط. |
| x2 | Single | الإحداثي الأفقي النهائي للخط. |
| y2 | Single | الإحداثي الرأسي النهائي للخط. |
| صفحة | Int32 | عدد الصفحة الأصلية التي سيُنشأ فيها التعليق. |
| border | Int32 | عرض الحدود بالنقاط. إذا كانت هذه القيمة 0 لن يتم رسم أي حد. القيمة الافتراضية هي 1. |
| clr | Color | لون الخط. |
| borderStyle | String | نمط الحدود الذي يحدد العرض ونمط الشرط لتُستخدم في رسم الخط. يمكن أن تكون هذه القيمة: "S" (متصل), "D" (متقطع), "B" (محدب), "I" (مُدخَل), "U" (تحتي). |
| dashArray | Int32[] | مصفوفة الشرط التي تحدد نمطًا من الشرط والفواصل لتُستخدم في رسم حد متقطع. إذا تم استخدامها، يجب ضبط borderSyle وفقًا لذلك على "D". |
| LEArray | String[] | مصفوفة من قيمتين تحددان على التوالي نمط البداية والنهاية للخط المرسوم. يمكن أن تكون القيم: "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash". |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


