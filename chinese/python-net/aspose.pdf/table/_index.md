---
title: "表格"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示可以添加到页面的表格。"
type: docs
weight: 1480
url: /zh/python-net/aspose.pdf/table/
---

## Table class

表示可以添加到页面的表格。

Table 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| Table() | 初始化 Table 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| vertical_alignment | 获取或设置段落的垂直对齐方式 |
| horizontal_alignment | 获取或设置段落的水平对齐方式 |
| margin | 获取或设置段落的外边距（用于 PDF 生成） |
| is_first_paragraph_in_column | 获取或设置一个布尔值，指示此段落是否将在下一列。<br/>            默认值为 false。（用于 PDF 生成） |
| is_kept_with_next | 获取或设置一个布尔值，指示当前段落是否与下一段落保持在同一页。<br/>            默认值为 false。（用于 PDF 生成） |
| is_in_new_page | 获取或设置一个布尔值，强制此段落在新页面生成。<br/>            默认值为 false。（用于 PDF 生成） |
| is_in_line_paragraph | 获取或设置段落是否为内联。<br/>            默认值为 false。（用于 PDF 生成） |
| hyperlink | 获取或设置片段超链接（用于 PDF 生成器）。 |
| z_index | 获取或设置一个整数值，指示 graph 的 Z 顺序。ZIndex 较大的 graph <br/>            将放置在 ZIndex 较小的 graph 之上。ZIndex 可以为负数。ZIndex 为负的 graph <br/>            将放置在页面文本的后面。 |
| background_color | 获取或设置表格背景颜色 |
| break_text | 获取或设置表的换行文本 |
| corner_style | 获取或设置边框角的样式 |
| repeating_rows_style | 获取重复行的样式 |
| repeating_columns_count | 获取或设置表的最大列数 |
| repeating_rows_count | 获取在多个页面上重复的首行数量 |
| column_widths | 获取表格的列宽。 |
| broken | 获取或设置表格垂直断开; |
| default_cell_border | 获取默认单元格边框； |
| default_column_width | 获取默认单元格边框； |
| 行 | 获取表的行。 |
| 边框 | 获取或设置边框。 |
| default_cell_padding | 获取或设置默认单元格内边距。 |
| default_cell_text_state | 获取或设置默认单元格文本状态。 |
| 对齐 | 获取或设置表格对齐方式。 |
| left | 获取或设置表格左坐标。 |
| top | 获取或设置表格顶部坐标。 |
| is_broken | 获取或设置表格是否断开 - 将在下一页截断。 |
| is_borders_included | 获取或设置列宽中包含的边框。 |
| column_adjustment | 获取或设置表格列的调整。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| clone() | 克隆表。 |
| get_width() | 获取宽度。 |
| get_height(parent_page) | 获取高度。 |
| set_column_text_state(col_number, text_state) | 设置高度。 |
| import_array(imported_array, first_filled_row, first_filled_column, is_left_columns_filled) | 将一维数据数组导入表中。导入过程每个数组项对应一个单元格，并<br/>              从参数中定义的行和列开始。导入时，如果检测到必要的行<br/>              仍然不存在（即目标表太小，无法容纳所有数据），将创建所需的行 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

