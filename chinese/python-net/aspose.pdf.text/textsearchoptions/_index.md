---
title: "TextSearchOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示文本搜索选项"
type: docs
weight: 460
url: /zh/python-net/aspose.pdf.text/textsearchoptions/
---

## TextSearchOptions class

表示文本搜索选项

TextSearchOptions 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| TextSearchOptions(is_regular_expression_used) | 初始化 TextSearchOptions 类的新实例 |
| TextSearchOptions(rectangle) | 初始化 TextSearchOptions 类的新实例 |
| TextSearchOptions(rectangle, is_regular_expression_used) | 初始化 TextSearchOptions 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| is_regular_expression_used | 获取或设置正则表达式是否被使用的指示。 |
| limit_to_page_bounds | 获取或设置指示文本是否在页面边界内搜索。 |
| rectangle | 获取或设置限定搜索文本的矩形。 |
| use_font_engine_encoding | 获取或设置指示文本将使用字体引擎编码进行搜索。<br/>            true - 表示将使用字体引擎编码（如果文本搜索因文档中编码不完整而失败，请尝试此设置）<br/>            false - 表示将使用文档字体编码（默认值） |
| ignore_shadow_text | 获取或设置指示在搜索期间将忽略表示普通文本阴影的文本片段。<br/>            true - 表示阴影文本将不会被找到（如果文本搜索在相近位置返回重复片段，请尝试此设置）<br/>            false - 表示阴影文本将与普通文本一起被找到（默认值） |
| log_text_extraction_errors | 获取或设置指示文本提取（解码）错误将在文本（片段）吸收器中记录。<br/>            true - 表示文本提取（解码）错误将被记录。这可能会降低性能。<br/>            false（默认）- 不记录错误。 |
| ignore_resource_font_errors | 获取或设置指示文本（片段）吸收器将忽略与缺少字体相关的错误。<br/>            true - 表示缺少字体的错误将被忽略。引用不正确资源的文本段将在处理过程中被跳过。<br/>            false（默认）- 缺少字体的错误将通过抛出异常终止处理。 |
| search_for_text_related_graphics | 获取或设置允许在文本搜索期间搜索文本相关图形（下划线、背景等）的值。<br/>            true - 将执行文本相关图形的搜索（默认值）。<br/>            false - 将忽略源文档中可能出现的图形元素。若出现性能问题或不需要处理下划线、背景或裁剪，可设置为此。 |
| stored_graphic_elements_max_count | 获取或设置限制在页面上搜索指定数量文本相关图形（下划线、背景等）的值。<br/>            默认值为 250。若出现性能问题可设置较小的值，若某些图形元素未被找到可尝试更大的值。 |
| search_in_annotations | 获取或设置允许在批注中搜索文本的值。<br/>            true - 将在批注中搜索文本。<br/>            false - 批注中的文本将不会被 TextFragmentAbsorber 解析。 |

### 另请参阅

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

