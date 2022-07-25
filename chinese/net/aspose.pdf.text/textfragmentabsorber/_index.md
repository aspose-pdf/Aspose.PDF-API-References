---
title: TextFragmentAbsorber
second_title: Aspose.PDF for .NET API 参考
description: 表示文本片段的吸收器对象 执行文本搜索并通过以下方式访问搜索结果TextFragments./textfragmentabsorber/textfragments集合.
type: docs
weight: 7110
url: /zh/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

表示文本片段的吸收器对象。 执行文本搜索并通过以下方式访问搜索结果[`TextFragments`](./textfragments)集合.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber#constructor)() | 初始化[`TextFragmentAbsorber`](../textfragmentabsorber)执行文档或页面的所有文本段的搜索。 |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_6)(Regex) | 初始化[`TextFragmentAbsorber`](../textfragmentabsorber)指定 System.Text.RegularExpressions.Regex 类对象的类。 |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_2)(string) | 初始化[`TextFragmentAbsorber`](../textfragmentabsorber)指定文本短语的类。 |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_1)(TextEditOptions) | 初始化[`TextFragmentAbsorber`](../textfragmentabsorber)带有文本编辑选项，执行文档或页面的所有文本段的搜索。 |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_7)(Regex, TextEditOptions) | 初始化[`TextFragmentAbsorber`](../textfragmentabsorber)指定文本短语和文本编辑选项的类。 |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_8)(Regex, TextSearchOptions) | 初始化[`TextFragmentAbsorber`](../textfragmentabsorber)指定文本短语和文本搜索选项的类。 |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_3)(string, TextEditOptions) | 初始化[`TextFragmentAbsorber`](../textfragmentabsorber)指定文本短语和文本编辑选项的类。 |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_4)(string, TextSearchOptions) | 初始化[`TextFragmentAbsorber`](../textfragmentabsorber)指定文本短语和文本搜索选项的类。 |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_5)(string, TextSearchOptions, TextEditOptions) | 初始化[`TextFragmentAbsorber`](../textfragmentabsorber)指定文本短语、文本搜索选项和文本编辑选项的类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors) { get; } | 列表[`TextExtractionError`](../textextractionerror)对象。它包含有关在文本提取期间发现错误的信息。 仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；它可能会降低性能。 |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions) { get; set; } | 获取或设置文本提取选项。 |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors) { get; } | 值表示在文本提取过程中是否发现错误。 只有在 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；它可能会降低性能。 |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase) { get; set; } | 获取或设置短语[`TextFragmentAbsorber`](../textfragmentabsorber)在 PDF 文档或页面上搜索。 |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text) { get; } | 获取提取的文本[`TextAbsorber`](../textabsorber)在 PDF 文档或页面上提取。 |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions) { get; set; } | 获取或设置文本编辑选项。当请求的符号不能用字体写入时，选项定义特殊行为。 |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments) { get; set; } | 获取出现的搜索事件的集合[`TextFragment`](../textfragment)对象. |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions) { get; set; } | 获取或设置文本替换选项。选项定义片段文本替换为更短/更长时的行为。 |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions) { get; set; } | 获取或设置搜索选项。选项启用使用正则表达式进行搜索。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_2)(float) | 为所有被吸收的文本片段应用字体大小。如果页面上的所有片段都被吸收，它比遍历片段更快。否则它与循环类似。 |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments)(Font) | 为所有被吸收的文本片段应用字体。如果页面上的所有片段都被吸收，它比遍历片段更快。否则它与循环类似。 |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_1)(Font, float) | 为所有被吸收的文本片段应用字体和大小。如果页面上的所有片段都被吸收，它比遍历片段更快。否则它与循环类似。 |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext)(Document) | 从文档中删除所有文本。 |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_1)(Page) | 删除指定页面中的所有文本。 |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_2)(Page, Rectangle) | 从指定页面中删除指定矩形内的文本。 |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset)() | 清除此 TextFragments 集合[`TextFragmentAbsorber`](../textfragmentabsorber)对象. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit)(Document) | 对指定文档执行搜索。 |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_1)(Page) | 在指定页面上执行搜索。 |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_2)(XForm) | 对指定的表单对象执行搜索。 |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit)(XForm) | 提取指定 XForm 上的文本。 |

### 评论

的[`TextFragmentAbsorber`](../textfragmentabsorber)对象基本上用于文本搜索场景。 搜索完成后，出现的次数用[`TextFragment`](../textfragment)对象[`TextFragments`](./textfragments)集合包含. [`TextFragment`](../textfragment)对象提供对搜索出现文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字体大小、颜色等）。

### 例子

该示例演示如何在第一个 PDF 文档页面上查找文本并替换文本及其字体。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 查找将用于更改文档文本字体的字体
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// 创建 TextFragmentAbsorber 对象以查找所有“hello world”文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改第一个文本出现的文本和字体
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 也可以看看

* class [TextAbsorber](../textabsorber)
* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
