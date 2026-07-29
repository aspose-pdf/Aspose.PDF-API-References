---
title: "类 FontRepository"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.FontRepository 类。执行字体搜索。搜索系统已安装的字体和标准 Pdf 字体。同时提供打开自定义字体的功能"
type: docs
weight: 10720
url: /zh/net/aspose.pdf.text/fontrepository/
---
## FontRepository class

执行字体搜索。搜索系统已安装的字体和标准 Pdf 字体。还提供打开自定义字体的功能。

```csharp
public sealed class FontRepository
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FontRepository](fontrepository/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | 获取字体来源集合。 |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | 获取字体替代策略集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | 搜索并返回具有指定字体名称的字体。 |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | 搜索并返回具有指定字体名称的字体，忽略或遵守大小写敏感性。 |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | 搜索并返回具有指定字体名称和字体样式的字体。 |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | 搜索并返回具有指定字体名称和字体样式的字体，忽略或遵守大小写敏感性。 |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | 加载系统已安装的字体和标准 Pdf 字体。此方法旨在加快字体加载过程。默认情况下，字体在首次请求任何字体时加载。使用此方法可在打开任何 Pdf 文档之前立即加载系统和标准 Pdf 字体。 |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | 使用指定的字体文件路径打开字体。 |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | 使用指定的字体流打开字体。 |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | 使用指定的字体文件路径和度量文件路径打开字体。 |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | 重新加载属性 [`Sources`](./sources/) 指定的所有字体。 |

## 示例

示例演示如何查找字体并替换首页文本的字体。

```csharp
// 查找字体
Font font = FontRepository.FindFont("Arial");

// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改首次出现的文本的字体
absorber.TextFragments[1].TextState.Font = font;

// 保存文档
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另请参见

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


