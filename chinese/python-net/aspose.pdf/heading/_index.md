---
title: "Heading"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示标题。"
type: docs
weight: 460
url: /zh/python-net/aspose.pdf/heading/
---

## Heading class

表示标题。

Heading 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| Heading(level) | 初始化 Heading 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| vertical_alignment | 获取或设置文本片段的垂直对齐方式。 |
| horizontal_alignment | 获取或设置文本片段的水平对齐方式。 |
| margin | 获取或设置段落的外边距（用于 PDF 生成） |
| is_first_paragraph_in_column | 获取或设置一个布尔值，指示此段落是否将在下一列。<br/>            默认值为 false。（用于 PDF 生成） |
| is_kept_with_next | 获取或设置一个布尔值，指示当前段落是否与下一段落保持在同一页。<br/>            默认值为 false。（用于 PDF 生成） |
| is_in_new_page | 获取或设置一个布尔值，强制此段落在新页面生成。<br/>            默认值为 false。（用于 PDF 生成） |
| is_in_line_paragraph | 获取或设置段落是否为内联。<br/>            默认值为 false。（用于 PDF 生成） |
| hyperlink | 设置片段的超链接 |
| z_index | 获取或设置一个整数值，指示 graph 的 Z 顺序。ZIndex 较大的 graph <br/>            将放置在 ZIndex 较小的 graph 之上。ZIndex 可以为负数。ZIndex 为负的 graph <br/>            将放置在页面文本的后面。 |
| replace_options | 获取文本替换选项。该选项定义在片段文本被替换为更短或更长时的行为。 |
| text | 获取或设置字符串文本对象，该对象由 [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 对象表示。 |
| text_state | 获取或设置文本状态，该状态对应 [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 对象所表示的文本。 |
| segments | 获取当前 [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 的文本段。 |
| position | 获取或设置文本位置，该文本由 [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 对象表示。<br/>            文本片段位置结构的 YIndent 表示基线坐标。 |
| baseline_position | 获取 TextFragment 的矩形。 |
| rectangle | 页面 |
| 获取包含 TextFragment 的页面。 | 获取包含 TextFragment 的表单对象。 |
| form | wrap_lines_count |
| 获取或设置此段落的换行行数（仅用于 PDF 生成）。 | end_note |
| 获取或设置段落尾注（仅用于 PDF 生成）。 | foot_note |
| 获取或设置段落脚注（仅用于 PDF 生成）。 | 获取或设置段落脚注。（仅用于 PDF 生成） |
| toc_page | 获取包含此标题的页面。 |
| top | 获取此标题的顶部 Y 坐标。 |
| start_number | 获取标题的起始编号。 |
| is_auto_sequence | 获取标题是否应自动编号。 |
| is_in_list | 获取标题是否应在目录列表中。 |
| destination_page | 获取目标页面。 |
| level | 获取级别。 |
| style | 获取或设置样式。 |
| user_label | 获取或设置用户标签。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| clone() | 克隆此标题。 |
| isolate_text_segments(start_index, length) | 获取表示指定部分的 [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(s)，该部分属于 [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 文本。 |
| clone_with_segments() | 克隆包含所有段的标题。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

