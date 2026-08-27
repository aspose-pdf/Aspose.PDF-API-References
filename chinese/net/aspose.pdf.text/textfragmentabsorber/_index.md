---
title: "类 TextFragmentAbsorber"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.TextFragmentAbsorber 类。表示文本片段的吸收器对象。执行文本搜索并通过 TextFragments 集合提供对搜索结果的访问。"
type: docs
weight: 11130
url: /zh/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

表示文本片段的吸收器对象。执行文本搜索并通过 [`TextFragments`](./textfragments/) 集合提供对搜索结果的访问。

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | 初始化 `TextFragmentAbsorber` 的新实例，该实例执行文档或页面所有文本段的搜索。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | 为指定的 System.Text.RegularExpressions.Regex 类对象初始化 `TextFragmentAbsorber` 类的新实例。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | 为指定的文本短语初始化 `TextFragmentAbsorber` 类的新实例。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | 使用文本编辑选项初始化 `TextFragmentAbsorber` 的新实例，该实例执行对文档或页面中所有文本段的搜索。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | 为指定的文本短语和文本编辑选项初始化 `TextFragmentAbsorber` 类的新实例。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | 为指定的文本短语和文本搜索选项初始化 `TextFragmentAbsorber` 类的新实例。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | 为指定的文本短语和文本搜索选项初始化 `TextFragmentAbsorber` 类的新实例。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | 为指定的文本短语和文本编辑选项初始化 `TextFragmentAbsorber` 类的新实例。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | 为指定的文本短语和文本搜索选项初始化 `TextFragmentAbsorber` 类的新实例。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | 为指定的文本短语、文本搜索选项和文本编辑选项初始化 `TextFragmentAbsorber` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | [`TextExtractionError`](../textextractionerror/) 对象的列表。它包含在文本提取期间发现的错误信息。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。 |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | 获取或设置文本提取选项。 |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | 该值指示在文本提取期间是否发现错误。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。 |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | 获取或设置 `TextFragmentAbsorber` 在 PDF Document 或 Page 上搜索的短语。 |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | 获取搜索出现次数的字典，以 System.Text.RegularExpressions.Regex 类作为键，[`TextFragment`](../textfragment/) 作为值。 |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | 获取 [`TextAbsorber`](../textabsorber/) 在 PDF Document 或 Page 上提取的文本。 |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | 获取或设置文本编辑选项。该选项定义当请求的符号无法使用字体写入时的特殊行为。 |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | 获取以 [`TextFragment`](../textfragment/) 对象呈现的搜索出现次数的集合。 |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | 获取或设置文本替换选项。该选项定义当片段文本被替换为更短或更长时的行为。 |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | 获取或设置搜索选项。该选项启用使用正则表达式的搜索。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | 为所有已吸收的文本片段应用字体大小。如果页面上的所有片段都已吸收，则其速度快于遍历片段；否则效果类似于遍历。 |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | 为所有已吸收的文本片段应用字体。如果页面上的所有片段都已吸收，则其速度快于遍历片段；否则效果类似于遍历。 |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | 为所有已吸收的文本片段同时应用字体和大小。如果页面上的所有片段都已吸收，则其速度快于遍历片段；否则效果类似于遍历。 |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | 从 Document 中移除所有文本。 |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | 从指定的 Page 中移除所有文本。 |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | 从指定的 Page 中移除位于指定矩形内的文本。 |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | 清除此 `TextFragmentAbsorber` 对象的 TextFragments 集合。 |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | 在指定的 Document 上执行搜索。 |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | 在指定的 Page 上执行搜索。 |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | 在指定的表单对象上执行搜索。 |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | 在指定的 XForm 上提取文本。 |

## 备注

`TextFragmentAbsorber` 对象主要用于文本搜索场景。搜索完成后，出现的结果以 [`TextFragment`](../textfragment/) 对象的形式表示，这些对象包含在 [`TextFragments`](./textfragments/) 集合中。[`TextFragment`](../textfragment/) 对象提供对搜索出现的文本、文本属性的访问，并允许编辑文本以及更改文本状态（字体、字体大小、颜色等）。

## 示例

示例演示了如何在第一个 PDF 文档页上查找文本并替换该文本及其字体。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 查找用于更改文档文本字体的字体
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改首次文本出现的文本和字体
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参见

* class [TextAbsorber](../textabsorber/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


