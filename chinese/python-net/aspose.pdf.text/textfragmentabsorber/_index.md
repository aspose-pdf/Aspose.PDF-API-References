---
title: "TextFragmentAbsorber"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示文本片段的吸收器对象。<br/>            执行文本搜索并通过 [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) 集合提供对搜索结果的访问。"
type: docs
weight: 400
url: /zh/python-net/aspose.pdf.text/textfragmentabsorber/
---

## TextFragmentAbsorber class

表示文本片段的吸收器对象。<br/>            执行文本搜索并通过 [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) 集合提供对搜索结果的访问。

TextFragmentAbsorber 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| TextFragmentAbsorber() | 初始化一个新的 [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) 实例，用于搜索文档或页面的所有文本段。 |
| TextFragmentAbsorber(text_edit_options) | 初始化 TextFragmentAbsorber 类的新实例 |
| TextFragmentAbsorber(phrase) | 初始化 TextFragmentAbsorber 类的新实例 |
| TextFragmentAbsorber(phrase, text_search_options) | 初始化 TextFragmentAbsorber 类的新实例 |
| TextFragmentAbsorber(phrase, text_search_options, text_edit_options) | 初始化 TextFragmentAbsorber 类的新实例 |
| TextFragmentAbsorber(phrase, text_edit_options) | 初始化 TextFragmentAbsorber 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| text | 获取 [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) 在 PDF 文档或页面上提取的文本。 |
| has_errors | 值指示在文本提取期间是否发现错误。<br/>仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。 |
| errors | [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/) 对象的列表。它包含在文本提取期间发现的错误信息。<br/>仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。 |
| extraction_options | 获取或设置文本提取选项。 |
| text_search_options | 获取或设置搜索选项。该选项支持使用正则表达式进行搜索。 |
| text_fragments | 获取使用 [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 对象表示的搜索匹配集合。 |
| phrase | 获取或设置 [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) 在 PDF 文档或页面上搜索的短语。 |
| text_edit_options | 获取或设置文本编辑选项。该选项定义当请求的符号无法使用字体写入时的特殊行为。 |
| text_replace_options | 获取或设置文本替换选项。该选项定义当片段文本被替换为更短或更长时的行为。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| visit(page) | 在指定页面上执行搜索。 |
| visit(pdf) | 对指定的文档执行搜索。 |
| visit(x_form) | 对指定的表单对象执行搜索。 |
| apply_for_all_fragments(font) | 为所有已吸收的文本片段应用字体。如果页面上的所有片段都已吸收，则它比遍历片段更快。否则，它的工作方式类似于遍历。 |
| apply_for_all_fragments(font_size) | 为所有已吸收的文本片段应用字体大小。如果页面上的所有片段都已吸收，则它比遍历片段更快。否则，它的工作方式类似于遍历。 |
| apply_for_all_fragments(font, font_size) | 为所有已吸收的文本片段同时应用字体和大小。如果页面上的所有片段都已吸收，则它比遍历片段更快。否则，它的工作方式类似于遍历。 |
| remove_all_text(page) | 从指定页面中移除所有文本。 |
| remove_all_text(page, rect) | 从指定页面中移除位于指定矩形内的文本。 |
| remove_all_text(document) | 从文档中移除所有文本。 |
| reset() | 清除此 [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) 对象的 TextFragments 集合。 |

### 另请参阅

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

