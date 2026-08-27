---
title: "类 Font"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.Font 类。表示字体对象。"
type: docs
weight: 10690
url: /zh/net/aspose.pdf.text/font/
---
## Font class

表示字体对象。

```csharp
public sealed class Font
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | 获取 PDF 字体对象的 BaseFont 值。也称为字体的 PostScript 名称。 |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | 有时 PDF 字体（通常是中、日、韩字体）可能具有特定的字体名称。该名称是 PDF 字体属性 "BaseFont" 的值，有时该属性会以十六进制形式表示。如果直接读取此名称，可能会呈现为不可读的形式。要获得可读形式，需要按照该字体特定的规则对字体名称进行解码。此属性返回解码后的字体名称，因此在遇到不可读的 [`FontName`](./fontname/) 时使用它。如果属性 [`FontName`](./fontname/) 已是可读形式，则此属性与 [`FontName`](./fontname/) 相同，因此在任何需要获取可读字体名称的情况下都可以使用此属性。 |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | 获取 `Font` 对象的字体名称。 |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | 用于调节 Font 行为的有用属性 |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | 获取指示字体是否已在系统中存在（已安装）的信息。 |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | 获取或设置指示字体是否已嵌入的值。基于 IFont 的字体将自动进行子集化并嵌入。 |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | 获取或设置指示字体是否为子集的值。基于 IFont 的字体将自动进行子集化并嵌入。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | 此方法的目标是返回嵌入字体失败时的错误描述。如果没有错误情况，则返回空字符串。 |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | 测量字符串。 |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | 将字体保存到流中。请注意，字体仅保存为中间的 TTF 格式，旨在仅用于原始文档的转换副本。该字体文件不应在原始文档上下文之外使用。 |

## 示例

示例演示了如何在首页搜索文本并更改首次匹配的字体。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 创建字体并标记为嵌入
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// 更改首次出现的文本的字体
absorber.TextFragments[1].TextState.Font = font;


// 保存文档
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另请参见

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [FontRepository](../fontrepository/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


