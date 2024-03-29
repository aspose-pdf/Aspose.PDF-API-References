---
title: HtmlSaveOptions.PartsEmbeddingModes
second_title: Aspose.PDF for .NET API 参考
description: 此枚举枚举 HTML 中引用的文件的可能嵌入模式 它允许控制引用的文件HTML字体图像CSSes 是嵌入到主 HTML 文件中还是生成为单独的二进制实体
type: docs
weight: 3580
url: /zh/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes enumeration

此枚举枚举 HTML 中引用的文件的可能嵌入模式 它允许控制引用的文件（HTML、字体、图像、CSSes） 是嵌入到主 HTML 文件中还是生成为单独的二进制实体

```csharp
public enum PartsEmbeddingModes
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | 强制将所有引用的文件（Css、图像、字体）嵌入到生成的 HTML 标记中（即嵌入到 HTML 本身中） 这种方法生成一个 HTML 文件，但输出的总大小 变得更大（因为正在使用二进制文件的 Base64 编码）和并非所有浏览器（尤其是旧版） 都能成功处理嵌入到 HTML 中的二进制文件。但它允许获取包含整个结果的 HTML，而无需任何其他文件。 |
| EmbedCssOnly | `1` | 强制将除 CSS（图像和字体）之外的所有引用文件分开browsers |
| NoEmbedding | `2` | 强制分开引用的文件（Css、图像、字体） 这种方法会生成一组文件，但输出的总大小 变得更小（因为没有使用二进制的 Base64 编码） 这种方法也会生成适用于广泛的浏览器 |

### 也可以看看

* class [HtmlSaveOptions](../htmlsaveoptions)
* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
