---
title: Enum HtmlSaveOptions.PartsEmbeddingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsPartsEmbeddingModes 枚举。此枚举列出了在 HTML 中引用的文件的可能嵌入模式。它允许控制引用的文件（HTML、字体、图像、CSS）是嵌入到主 HTML 文件中，还是作为单独的二进制实体生成。
type: docs
weight: 5710
url: /zh/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes 枚举

此枚举列出了在 HTML 中引用的文件的可能嵌入模式。它允许控制引用的文件（HTML、字体、图像、CSS）是嵌入到主 HTML 文件中，还是作为单独的二进制实体生成。

```csharp
public enum PartsEmbeddingModes
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | 强制将所有引用的文件（CSS、图像、字体）嵌入生成的 HTML 标记中（即嵌入到 HTML 本身中）。这种方法生成一个 HTML 文件，但输出的总大小变得更大（因为使用了二进制的 Base64 编码），并且并非所有浏览器（尤其是旧版浏览器）都能成功处理嵌入到 HTML 中的二进制文件。但它允许获取包含整个结果的 HTML，而无需任何附加文件。 |
| EmbedCssOnly | `1` | 强制将所有引用的文件放在外部，除了 CSS（图像和字体）。即 CSS 将嵌入到结果 HTML 中，所有其他引用的文件（图像和字体）将作为外部部分处理。它生成适合广泛浏览器集的 HTML。 |
| NoEmbedding | `2` | 强制将引用的文件（CSS、图像、字体）放在外部。这种方法生成一组文件，但输出的总大小变得更小（因为不使用二进制的 Base64 编码）。这种方法还生成适合广泛浏览器集的 HTML。 |

### 另请参阅

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)