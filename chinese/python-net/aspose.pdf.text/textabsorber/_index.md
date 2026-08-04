---
title: "TextAbsorber"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示文本的吸收器对象。<br/>            执行文本提取并通过 [text](/pdf/python-net/aspose.pdf.text/textabsorber/) 对象提供对结果的访问。"
type: docs
weight: 320
url: /zh/python-net/aspose.pdf.text/textabsorber/
---

## TextAbsorber class

表示文本的吸收器对象。<br/>            执行文本提取并通过 [text](/pdf/python-net/aspose.pdf.text/textabsorber/) 对象提供对结果的访问。

TextAbsorber 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| TextAbsorber() | 初始化一个新的 [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) 实例。 |
| TextAbsorber(extraction_options) | 初始化 TextAbsorber 类的新实例 |
| TextAbsorber(extraction_options, text_search_options) | 初始化 TextAbsorber 类的新实例 |
| TextAbsorber(text_search_options) | 初始化 TextAbsorber 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| text | 获取 [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) 在 PDF 文档或页面上提取的文本。 |
| has_errors | 值指示在文本提取期间是否发现错误。<br/>仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。 |
| errors | [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/) 对象的列表。它包含在文本提取期间发现的错误信息。<br/>仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。 |
| extraction_options | 获取或设置文本提取选项。 |
| text_search_options | 获取或设置文本搜索选项。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| visit(page) | 提取指定页面上的文本 |
| visit(form) | 提取指定 XForm 上的文本。 |
| visit(pdf) | 提取指定文档中的文本 |

### 另请参阅

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

