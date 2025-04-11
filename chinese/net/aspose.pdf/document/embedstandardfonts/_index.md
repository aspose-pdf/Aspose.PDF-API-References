---
title: Document.EmbedStandardFonts
second_title: Aspose.PDF for .NET API Reference
description: 文档属性。声明文档必须嵌入所有标准 Type1 字体，这些字体的标志 IsEmbedded 设置为 true。所有 PDF 字体可以通过将标志 IsEmbedded 设置为 true 简单地嵌入文档，但 PDF 标准 Type1 字体是此规则的例外。标准 Type1 字体的嵌入需要大量时间，因此要嵌入这些字体，不仅需要为指定字体设置标志 IsEmbedded 为 true，还需要在文档级别设置一个额外的标志 - EmbedStandardFonts = true；此属性只能为所有字体设置一次。默认值为 false。
type: docs
weight: 150
url: /zh/net/aspose.pdf/document/embedstandardfonts/
---
## Document.EmbedStandardFonts 属性

声明文档必须嵌入所有标准 Type1 字体，这些字体的标志 IsEmbedded 设置为 true。所有 PDF 字体可以通过将标志 IsEmbedded 设置为 true 简单地嵌入文档，但 PDF 标准 Type1 字体是此规则的例外。标准 Type1 字体的嵌入需要大量时间，因此要嵌入这些字体，不仅需要为指定字体设置标志 IsEmbedded 为 true，还需要在文档级别设置一个额外的标志 - EmbedStandardFonts = true；此属性只能为所有字体设置一次。默认值为 false。

```csharp
public bool EmbedStandardFonts { get; set; }
```

### 另请参阅

* 类 [Document](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)