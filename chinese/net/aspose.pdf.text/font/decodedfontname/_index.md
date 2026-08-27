---
title: "Font.DecodedFontName"
second_title: "Aspose.PDF for .NET API 参考"
description: "Font 属性。有时 PDF 字体（通常是中文/日文/韩文字体）可能具有特定的字体名称。该名称是 PDF 字体属性 BaseFont 的值，有时该属性可能以十六进制形式表示。如果直接读取此名称，可能呈现为不可读的形式。要获得可读形式，需要按照该字体的特定规则对字体名称进行解码。此属性返回解码后的字体名称，因此在遇到不可读的 FontName 时使用它。如果属性 FontName 已是可读形式，则此属性与 FontName 相同，您可以在任何需要获取可读字体名称的情况下使用此属性。"
type: docs
weight: 20
url: /zh/net/aspose.pdf.text/font/decodedfontname/
---
## Font.DecodedFontName property

有时 PDF 字体（通常是中文/日文/韩文字体）可能具有特定的字体名称。该名称是 PDF 字体属性 "BaseFont" 的值，有时该属性可能以十六进制形式表示。如果直接读取此名称，可能呈现为不可读的形式。要获得可读形式，需要按照该字体的特定规则对字体名称进行解码。此属性返回解码后的字体名称，因此在遇到不可读的 [`FontName`](../fontname/) 时使用它。如果属性 [`FontName`](../fontname/) 已是可读形式，则此属性与 [`FontName`](../fontname/) 相同，您可以在任何需要获取可读字体名称的情况下使用此属性。

```csharp
public string DecodedFontName { get; }
```

### 另请参见

* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


