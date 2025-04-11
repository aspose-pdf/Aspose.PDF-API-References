---
title: PdfContentEditor.CreateLine
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ تعليق خط
type: docs
weight: 180
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## طريقة PdfContentEditor.CreateLine

تنشئ تعليق خط.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | مستطيل التعليق الذي يحدد موقع التعليق على الصفحة. |
| contents | String | محتويات التعليق. |
| x1 | Single | الإحداثي الأفقي الابتدائي للخط. |
| y1 | Single | الإحداثي العمودي الابتدائي للخط. |
| x2 | Single | الإحداثي الأفقي النهائي للخط. |
| y2 | Single | الإحداثي العمودي النهائي للخط. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق. |
| border | Int32 | عرض الحدود بالنقاط. إذا كانت هذه القيمة 0، فلن يتم رسم أي حدود. القيمة الافتراضية هي 1. |
| clr | Color | لون الخط. |
| borderStyle | String | نمط الحدود الذي يحدد العرض ونمط الخط المستخدم في رسم الخط. يمكن أن تكون هذه القيمة: "S" (صلب)، "D" (مخطط)، "B" (مائل)، "I" (مدرج)، "U" (تسطير). |
| dashArray | Int32[] | مصفوفة مخطط تحدد نمط الخطوط والفجوات المستخدمة في رسم حد مخطط. إذا تم استخدامها، يجب تعيين borderSyle وفقًا لذلك إلى "D". |
| LEArray | String[] | مصفوفة من قيمتين تحدد على التوالي نمط بداية ونهاية الخط المرسوم. يمكن أن تكون القيم: "مربع"، "دائرة"، "ماس"، "سهم مفتوح"، "سهم مغلق"، "لا شيء"، "مستقيم"، "سهم مفتوح يمين"، "سهم مغلق يمين"، "شريحة". |

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