---
title: Class Font
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.Font 类。表示字体对象
type: docs
weight: 10510
url: /zh/net/aspose.pdf.text/font/
---
## 字体类

表示字体对象。

```csharp
public sealed class Font
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | 获取 PDF 字体对象的 BaseFont 值。也称为字体的 PostScript 名称。 |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | 有时 PDF 字体（通常是中文/日文/韩文字体）可能具有特定的字体名称。此名称是 PDF 字体属性 "BaseFont" 的值，有时该属性可能以十六进制形式表示。如果直接读取此名称，可能会以不可读的形式表示。要获取可读形式，必须根据该字体特定的规则解码字体名称。此属性返回解码后的字体名称，因此在遇到不可读的 [`FontName`](./fontname/) 时使用。如果属性 [`FontName`](./fontname/) 具有可读形式，则此属性将与 [`FontName`](./fontname/) 相同，因此在需要以可读形式获取字体名称的任何情况下都可以使用此属性。 |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | 获取 `Font` 对象的字体名称。 |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | 用于调整字体行为的有用属性 |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | 获取指示字体是否存在（已安装）在系统中的值。 |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | 获取或设置一个值，指示字体是否嵌入。基于 IFont 的字体将自动被子集化并嵌入 |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | 获取或设置一个值，指示字体是否为子集。基于 IFont 的字体将自动被子集化并嵌入 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | 此方法的目标是返回描述错误的内容，如果嵌入字体的尝试失败。如果没有错误情况，它返回空字符串。 |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | 测量字符串。 |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | 将字体保存到流中。请注意，字体保存为中间 TTF 格式，仅用于转换后的原始文档副本。字体文件不打算在原始文档上下文之外使用。 |

## 示例

该示例演示如何在第一页上搜索文本并更改第一个搜索结果的字体。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;


// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另请参阅

* 类 [TextFragmentAbsorber](../textfragmentabsorber/)
* 类 [FontRepository](../fontrepository/)
* 类 [Document](../../aspose.pdf/document/)
* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../)