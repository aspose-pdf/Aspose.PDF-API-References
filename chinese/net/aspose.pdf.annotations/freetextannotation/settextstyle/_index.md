---
title: "FreeTextAnnotation.SetTextStyle"
second_title: "Aspose.PDF for .NET API 参考"
description: "FreeTextAnnotation 方法。设置由参数 textStyle 决定的所有注释文本的格式"
type: docs
weight: 150
url: /zh/net/aspose.pdf.annotations/freetextannotation/settextstyle/
---
## SetTextStyle(RichTextFontStyles, string, double, Color) {#settextstyle}

为所有注释文本设置由参数 textStyle 确定的格式。

```csharp
public void SetTextStyle(RichTextFontStyles textStyles, string fontName, double fontSize, 
    Color fontColor)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textStyles | RichTextFontStyles | 应用于注释文本的样式。 |
| fontName | String | 应用于注释文本的字体名称。 |
| fontSize | Double | 应用于注释文本的字体大小。 |
| fontColor | Color | 应用于注释文本的字体颜色。 |

### 另请参见

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetTextStyle(int, int, RichTextFontStyles) {#settextstyle_1}

为从 fromInd 索引到 toInd 索引的文本片段设置由参数 textStyle 确定的格式。

```csharp
public void SetTextStyle(int fromInd, int toInd, RichTextFontStyles textStyles)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fromInd | Int32 | 文本片段的起始索引（从 0 开始）。 |
| toInd | Int32 | 文本片段的结束索引（从 0 开始计数，不包括该索引）。 |
| textStyles | RichTextFontStyles | 应用于文本片段的样式。 |

### 另请参见

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


