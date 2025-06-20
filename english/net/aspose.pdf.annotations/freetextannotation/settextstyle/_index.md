---
title: FreeTextAnnotation.SetTextStyle
second_title: Aspose.PDF for .NET API Reference
description: FreeTextAnnotation method. Sets the formatting determined by the parameter textStyle for all annotation text
type: docs
weight: 150
url: /net/aspose.pdf.annotations/freetextannotation/settextstyle/
---
## SetTextStyle(RichTextFontStyles, string, double, Color) {#settextstyle}

Sets the formatting determined by the parameter textStyle for all annotation text.

```csharp
public void SetTextStyle(RichTextFontStyles textStyles, string fontName, double fontSize, 
    Color fontColor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| textStyles | RichTextFontStyles | Style(s) applied for annotation text. |
| fontName | String | Font name applied for annotation text. |
| fontSize | Double | Font size applied for annotation text. |
| fontColor | Color | Font color applied for annotation text. |

### See Also

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetTextStyle(int, int, RichTextFontStyles) {#settextstyle_1}

Sets the formatting determined by the parameter textStyle for a text fragment from fromInd index to toInd index.

```csharp
public void SetTextStyle(int fromInd, int toInd, RichTextFontStyles textStyles)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fromInd | Int32 | Starting index of the text fragment (from 0). |
| toInd | Int32 | End index of the text fragment (counting from 0, this not included). |
| textStyles | RichTextFontStyles | Style(s) applied for text fragment. |

### See Also

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


