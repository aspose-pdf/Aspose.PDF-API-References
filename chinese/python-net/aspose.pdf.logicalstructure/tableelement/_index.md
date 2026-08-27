---
title: "TableElement"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示逻辑结构中的 Table 结构元素。"
type: docs
weight: 610
url: /zh/python-net/aspose.pdf.logicalstructure/tableelement/
---

## TableElement class

表示逻辑结构中的 Table 结构元素。

TableElement 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| parent_element | None |
| child_elements | None |
| default_attribute_owner | 获取 |
| 属性 | 获取 |
| structure_type | 获取结构元素的类型。 |
| id | 获取结构元素的 ID。 |
| 标题 | 获取或设置结构元素的标题。 |
| language | 获取或设置结构元素的语言。 |
| alternative_text | 获取或设置结构元素的替代文本。 |
| expansion_text | 获取或设置结构元素的展开文本。 |
| actual_text | 获取或设置结构元素的实际文本。 |
| background_color | 获取或设置表格的背景颜色。 |
| 边框 | 获取或设置表格边框。 |
| 对齐 | 获取或设置表格对齐方式。 |
| corner_style | 获取或设置边框角的样式 |
| broken | 获取或设置表格垂直断开; |
| column_adjustment | 获取或设置表格列的调整。 |
| column_widths | 获取表格的列宽。 |
| default_cell_border | 获取默认单元格边框。 |
| default_cell_padding | 获取或设置默认单元格内边距。 |
| default_cell_text_state | 获取或设置默认单元格文本状态。 |
| default_column_width | 获取或设置默认列宽。 |
| is_broken | 获取或设置表格是否断开 - 将在下一页截断。 |
| is_borders_included | 获取或设置列宽中包含的边框。 |
| left | 获取或设置表格左坐标。 |
| top | 获取或设置表格顶部坐标。 |
| repeating_columns_count | 获取或设置表的最大列数。 |
| repeating_rows_count | 获取在多个页面上重复的首行计数。 |
| repeating_rows_style | 获取重复行的样式。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| append_child(element) | None |
| change_parent_element(new_parent_element) | 更改当前结构元素的父元素 |
| generate_id() | 为结构元素生成 ID。 |
| set_id(id) | 设置结构元素的 ID。 |
| clear_id() | 清除结构元素的 ID。 |
| set_tag(new_tag) | 为结构元素设置自定义标签。 |
| create_t_head() | 创建 [TableTHeadElement](/pdf/python-net/aspose.pdf.logicalstructure/tabletheadelement/) 并将其添加到当前表中。 |
| create_t_body() | 创建 [TableTHeadElement](/pdf/python-net/aspose.pdf.logicalstructure/tabletheadelement/) 并将其添加到当前表中。 |
| create_t_foot() | 创建 [TableTFootElement](/pdf/python-net/aspose.pdf.logicalstructure/tabletfootelement/) 并将其添加到当前表中。 |

### 另请参阅

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

