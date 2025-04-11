---
title: Font.DecodedFontName
second_title: Aspose.PDF for .NET API Reference
description: 字体属性。有时 PDF 字体（通常是中文/日文/韩文字体）可能具有特定的字体名称。这个名称是 PDF 字体属性 BaseFont 的值，有时这个属性可以以十六进制形式表示。如果直接读取这个名称，它可能以不可读的形式表示。要获得可读的形式，必须按照特定于该字体的规则解码字体名称。此属性返回解码后的字体名称，因此在遇到不可读的 [`FontName`](../fontname/) 时使用它。如果属性 [`FontName`](../fontname/) 具有可读形式，则此属性将与 [`FontName`](../fontname/) 相同，因此您可以在需要以可读形式获取字体名称的任何情况下使用此属性。
type: docs
weight: 20
url: /zh/net/aspose.pdf.text/font/decodedfontname/
---
## Font.DecodedFontName 属性

有时 PDF 字体（通常是中文/日文/韩文字体）可能具有特定的字体名称。这个名称是 PDF 字体属性 "BaseFont" 的值，有时这个属性可以以十六进制形式表示。如果直接读取这个名称，它可能以不可读的形式表示。要获得可读的形式，必须按照特定于该字体的规则解码字体名称。此属性返回解码后的字体名称，因此在遇到不可读的 [`FontName`](../fontname/) 时使用它。如果属性 [`FontName`](../fontname/) 具有可读形式，则此属性将与 [`FontName`](../fontname/) 相同，因此您可以在需要以可读形式获取字体名称的任何情况下使用此属性。

```csharp
public string DecodedFontName { get; }
```

### 另请参见

* 类 [Font](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)