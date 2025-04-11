---
title: Class FontRepository
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.FontRepository 类。执行字体搜索。在系统安装的字体和标准 Pdf 字体中进行搜索。还提供打开自定义字体的功能
type: docs
weight: 10540
url: /zh/net/aspose.pdf.text/fontrepository/
---
## FontRepository class

执行字体搜索。在系统安装的字体和标准 Pdf 字体中进行搜索。还提供打开自定义字体的功能。

```csharp
public sealed class FontRepository
```

## Constructors

| Name | Description |
| --- | --- |
| [FontRepository](fontrepository/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | 获取字体源集合。 |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | 获取字体替代策略集合。 |

## Methods

| Name | Description |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | 搜索并返回指定字体名称的字体。 |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | 搜索并返回指定字体名称的字体，忽略或尊重大小写敏感性。 |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | 搜索并返回指定字体名称和字体样式的字体。 |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | 搜索并返回指定字体名称和字体样式的字体，忽略或尊重大小写敏感性。 |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | 加载系统安装的字体和标准 Pdf 字体。此方法旨在加快字体加载过程。默认情况下，字体在首次请求任何字体时加载。使用此方法会在打开任何 Pdf 文档之前立即加载系统和标准 Pdf 字体。 |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | 打开指定字体文件路径的字体。 |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | 打开指定字体流的字体。 |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | 打开指定字体文件路径和度量文件路径的字体。 |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | 重新加载由属性 [`Sources`](./sources/) 指定的所有字体。 |

## Examples

该示例演示如何查找字体并替换第一页文本的字体。

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### See Also

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)