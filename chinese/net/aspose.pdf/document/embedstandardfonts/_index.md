---
title: "Document.EmbedStandardFonts"
second_title: "Aspose.PDF for .NET API 参考"
description: "Document 属性。 声明文档必须嵌入所有标准 Type1 字体，并将标志 IsEmbedded 设置为 true。 所有 PDF 字体都可以通过将标志 IsEmbedded 设置为 true 来嵌入文档，但 PDF 标准 Type1 字体是此规则的例外。 嵌入标准 Type1 字体需要大量时间，因此要嵌入这些字体，不仅需要为指定字体将标志 IsEmbedded 设置为 true，还必须在文档级别设置额外的标志 EmbedStandardFonts 为 true。 此属性只能为所有字体设置一次。 默认值为 false"
type: docs
weight: 160
url: /zh/net/aspose.pdf/document/embedstandardfonts/
---
## Document.EmbedStandardFonts property

声明文档必须嵌入所有标准 Type1 字体的属性，该属性将标志 IsEmbedded 设置为 true。所有 PDF 字体都可以通过将 IsEmbedded 标志设为 true 来嵌入文档，但 PDF 标准 Type1 字体是例外。嵌入标准 Type1 字体需要较长时间，因此除了为指定字体将 IsEmbedded 标志设为 true 外，还必须在文档级别设置额外的标志 - EmbedStandardFonts = true；此属性只能对所有字体设置一次。默认值为 false。

```csharp
public bool EmbedStandardFonts { get; set; }
```

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


