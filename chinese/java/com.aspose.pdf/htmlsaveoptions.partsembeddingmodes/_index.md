---
title: "HtmlSaveOptions.PartsEmbeddingModes"
linktitle: "HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Aspose.PDF for Java API 参考"
description: "此枚举列举了在 HTML 中引用的文件的可能嵌入模式，允许控制是否将引用的文件（HTML、字体、图像、CSS）嵌入到主文件中。"
type: docs
weight: 2130
url: /zh/java/com.aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes

```
public static final class HtmlSaveOptions.PartsEmbeddingModes extends com.aspose.ms.System.Enum
```

此枚举列举了在 HTML 中嵌入引用文件的可能模式。它允许控制引用的文件（HTML、字体、图像、CSS）是嵌入到主 HTML 文件中，还是作为独立的二进制实体生成

## 字段

| 字段 | 描述 |
| --- | --- |
| [EmbedAllIntoHtml](#EmbedAllIntoHtml) | 强制将所有引用的文件（Css、图像、字体）嵌入生成的 HTML 标记中（即嵌入到 HTML 本身）。此方法会生成一个 HTML 文件，但输出的总体积会变大（因为使用了二进制的 Base64 编码），且并非所有浏览器（尤其是旧版）都能成功处理嵌入到 HTML 中的二进制。但它可以获得包含完整结果的 HTML，无需任何额外文件。 |
| [EmbedCssOnly](#EmbedCssOnly) | 强制将除 CSS 之外的所有引用文件分离（图像和字体）。即 CSS 将嵌入到生成的 HTML 中，而所有其他引用文件（图像和字体）将作为外部部件处理。它生成的 HTML 适用于大多数浏览器。 |
| [NoEmbedding](#NoEmbedding) | 强制将引用的文件（Css、图像、字体）分离。此方法会生成一组文件，但输出的总体积会更小（因为未使用二进制的 Base64 编码）。同样，该方法生成的 HTML 适用于大多数浏览器。 |

### EmbedAllIntoHtml {#EmbedAllIntoHtml}
```
public static final int EmbedAllIntoHtml
```

强制将所有引用的文件（Css、图像、字体）嵌入生成的 HTML 标记中（即嵌入到 HTML 本身）。此方法会生成一个 HTML 文件，但输出的总体积会变大（因为使用了二进制的 Base64 编码），且并非所有浏览器（尤其是旧版）都能成功处理嵌入到 HTML 中的二进制。但它可以获得包含完整结果的 HTML，无需任何额外文件。

### EmbedCssOnly {#EmbedCssOnly}
```
public static final int EmbedCssOnly
```

强制将除 CSS 之外的所有引用文件分离（图像和字体）。即 CSS 将嵌入到生成的 HTML 中，而所有其他引用文件（图像和字体）将作为外部部件处理。它生成的 HTML 适用于大多数浏览器。

### NoEmbedding {#NoEmbedding}
```
public static final int NoEmbedding
```

强制将引用的文件（Css、图像、字体）分离。此方法会生成一组文件，但输出的总体积会更小（因为未使用二进制的 Base64 编码）。同样，该方法生成的 HTML 适用于大多数浏览器。
