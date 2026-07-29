---
title: "FreeTextAnnotation.SetTextStyle"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FreeTextAnnotation. يعيّن التنسيق المحدد بواسطة المعامل textStyle لجميع نصوص التعليق."
type: docs
weight: 150
url: /ar/net/aspose.pdf.annotations/freetextannotation/settextstyle/
---
## SetTextStyle(RichTextFontStyles, string, double, Color) {#settextstyle}

يضبط التنسيق المحدد بواسطة المعامل textStyle لجميع نصوص التعليق.

```csharp
public void SetTextStyle(RichTextFontStyles textStyles, string fontName, double fontSize, 
    Color fontColor)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| textStyles | RichTextFontStyles | النمط(ات) المطبقة على نص التعليق. |
| fontName | String | اسم الخط المطبق على نص التعليق. |
| fontSize | Double | حجم الخط المطبق على نص التعليق. |
| fontColor | Color | لون الخط المطبق على نص التعليق. |

### انظر أيضًا

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetTextStyle(int, int, RichTextFontStyles) {#settextstyle_1}

يضبط التنسيق المحدد بواسطة المعامل textStyle لجزء نص من الفهرس fromInd إلى الفهرس toInd.

```csharp
public void SetTextStyle(int fromInd, int toInd, RichTextFontStyles textStyles)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fromInd | Int32 | الفهرس الابتدائي لمقاطع النص (من 0). |
| toInd | Int32 | الفهرس النهائي لمقاطع النص (يُحسب من 0، ولا يُضمّن هذا). |
| textStyles | RichTextFontStyles | الأنماط المطبقة على مقطع النص. |

### انظر أيضًا

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


