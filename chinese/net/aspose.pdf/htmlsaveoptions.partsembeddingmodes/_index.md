---
title: "枚举 HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.HtmlSaveOptionsPartsEmbeddingModes 枚举。此枚举列举了在 HTML 中引用的文件的可能嵌入模式。它允许控制引用的文件（HTML、字体、图像、CSS）是嵌入到主 HTML 文件中，还是生成独立的二进制实体。"
type: docs
weight: 5840
url: /zh/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes enumeration

此枚举列举了在 HTML 中引用的文件的可能嵌入模式。它允许控制引用的文件（HTML、字体、图像、CSS）是嵌入到主 HTML 文件中，还是生成独立的二进制实体。

```csharp
public enum PartsEmbeddingModes
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | 强制将所有引用的文件（CSS、图像、字体）嵌入生成的 HTML 标记中（即嵌入到 HTML 本身）。此方法生成一个 HTML 文件，但输出的总体积会更大（因为使用了二进制的 Base64 编码），且并非所有浏览器（尤其是旧版）都能成功处理嵌入 HTML 的二进制。但它可以获得包含完整结果的 HTML，无需任何额外文件。 |
| EmbedCssOnly | `1` | 强制将除 CSS 之外的所有引用文件（图像和字体）分离。即 CSS 将嵌入到生成的 HTML 中，而其他引用文件（图像和字体）将作为外部部件处理。此方式生成的 HTML 适用于大多数浏览器。 |
| NoEmbedding | `2` | 强制将引用的文件（CSS、图像、字体）分离。此方法会生成一组文件，但输出的总体积更小（因为未使用二进制的 Base64 编码）。同样，这种方式生成的 HTML 适用于大多数浏览器。 |

### 另请参见

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


